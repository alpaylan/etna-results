# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`
  left: `[(1..3, false), (3..5, false)]`,
 right: `[(1..5, false)]`'), and passed after restoration

Upstream: https://github.com/jeffparsons/rangemap

Candidate: d1999f48003b43ec7ed598c9497b859a8302b897-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 85 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
