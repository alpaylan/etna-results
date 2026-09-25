# etna-results

System of record for [etna-ify](https://github.com/alpaylan/etna-ify) bug
mining: the durable dataset of historical regressions reproduced with
unchanged upstream tests.

This repository holds the candidate queue and the per-upstream inventories.
Workflow artifacts on the runner side keep transient full logs for 30 days;
**this repository is the dataset**.

## Layout

```text
queue.jsonl                              candidate queue (see write protocol)
<upstream>/bugs.jsonl                    append-only candidate inventory snapshots
<upstream>/scan.json                     history coverage checkpoint
<upstream>/patches/<id>/<attempt>.patch  implementation-reversal patches
<upstream>/evidence/<id>/<attempt>/      logs, environment, lockfiles
<upstream>/summary.md                    latest outcome and coverage
```

`<upstream>` is the upstream project name, e.g. `rust-base64`. Candidates
are imported from the prior `alpaylan/*-etna` trials and reproduced under
the contracts in etna-ify (`docs/provenance-tiers.md`,
`docs/cloud-execution.md`, `skills/`).

See [CONFIRMED.md](CONFIRMED.md) for the human-readable index of every
confirmed bug (regenerated nightly by the discovery workflow).

## Write protocol

- Append-only JSONL; the last complete record per ID is the current state.
  Never rewrite or reorder history.
- Queue records move `pending → claimed{run_id, claimed_at} → terminal`;
  the latest record per candidate wins.
- The git push is the compare-and-swap: one writer per push, retry with
  rebase on rejection.
- Claims older than about two hours without a terminal record may be
  re-opened by the scheduler.
- Confirmed records carry `reproduction.provenance` of `verbatim` or
  `adapted`; adapted records include an `anchor` referencing the verbatim
  reference comparison. Evidence hashes in each record allow replay
  verification.

## Consumers

Filter confirmed records on `reproduction.provenance`. Status counts and
coverage are per upstream in each `summary.md`; unresolved candidates keep
explicit reasons (`blocked`, `unconfirmed`) and are legitimate dataset
content, not failures.
