# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('called `Result::unwrap_err()` on an `Ok` value: 0'), and passed after restoration

Upstream: https://github.com/rust-num/num-bigint

Candidate: 5dcf2a1deb1b8e2e225521cb103ee90a8c70b666-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 1200 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
