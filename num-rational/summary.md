# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`
  left: `Ratio { numer: 0, denom: 1 }`,
 right: `Ratio { numer: 0, denom: 2 }`'), and passed after restoration

Upstream: https://github.com/rust-num/num-rational

Candidate: e10ca814e7b1f4d5fcc42ed5e7ceb39f8443ef5c-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 774 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
