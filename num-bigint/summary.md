# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('called `Option::unwrap()` on a `None` value'), and passed after restoration

Upstream: https://github.com/rust-num/num-bigint

Candidate: 0940e509dca55d19197adbe7cb5c1d5423a390cf-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 1225 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
