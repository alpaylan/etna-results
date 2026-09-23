# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: (0.6 - jaro("a jke", "jane a k")).abs() < 0.001'), and passed after restoration

Upstream: https://github.com/rapidfuzz/strsim-rs

Candidate: 5b512dce33d186f4fbe7ed3fa7a5dc7e33d73823-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 91 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
