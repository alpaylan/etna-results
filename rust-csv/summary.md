# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`
  left: `"# comment,another\n"`,
 right: `"\"# comment\",another\n"`'), and passed after restoration

Upstream: https://github.com/BurntSushi/rust-csv

Candidate: 0f64d3f3322b30af7a38e222bd7dad18eac38b2b-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 451 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
