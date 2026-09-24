# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`
  left: `[0, 0, 0, 0, 0, 0, 0, 0, 0]`,
 right: `[33, 49, 50, 51, 101, 120, 49, 50, 51]`'), and passed after restoration

Upstream: https://github.com/tokio-rs/bytes

Candidate: 0a2c43af8811fecf6fd08379f16571594bcbb738-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 424 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
