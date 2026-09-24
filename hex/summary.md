# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`

[1mDiff[0m [31m< left[0m / [32mright >[0m :
[31m<[0m[31m"Invalid character \'\[0m[31mn\' at position 5"[0m
[32m>[0m[32m"Invalid character \'\[0m[1;48;5;22;32m\[0m[32mn\' at position 5"[0m'), and passed after restoration

Upstream: https://github.com/KokaKiwi/rust-hex

Candidate: 764ee61536cbeb8cfbce6dba61c1b85398700bb6-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 55 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
