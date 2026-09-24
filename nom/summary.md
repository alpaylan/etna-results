# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion `left == right` failed
  left: Ok(("", ""))
 right: Ok(("", "\n"))'), and passed after restoration

Upstream: https://github.com/rust-bakery/nom

Candidate: 51c3c4e44fa78a8a09b413419372b97b2cc2a787-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 2751 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
