# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left != right)`
  left: `ByteRecord(["12", "34", "56"])`,
 right: `ByteRecord(["12", "34"])`'), and passed after restoration

Upstream: https://github.com/BurntSushi/rust-csv

Candidate: 23fb0cd676bf71c23fc8de45856cbf0187627e45-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 381 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
