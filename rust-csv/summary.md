# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left != right)`
  left: `ByteRecord(["12", "34"])`,
 right: `ByteRecord(["123", "4"])`'), and passed after restoration

Upstream: https://github.com/BurntSushi/rust-csv

Candidate: efc4a51224dd6ccb1b1c4e2254a1ea94b9067b17-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 379 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
