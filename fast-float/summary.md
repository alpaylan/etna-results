# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`
  left: `9007199254740994.0`,
 right: `9007199254740992.0`'), and passed after restoration

Upstream: https://github.com/aldanor/fast-float-rust

Candidate: 56ac048a96c10c014d5398bae9e548b929616228-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 67 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
