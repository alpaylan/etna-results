# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`

[1mDiff[0m [31m< left[0m / [32mright >[0m :
[31m<[0m[31m0[0m
[32m>[0m[1;48;5;22;32m1[0m[32m0[0m[1;48;5;22;32m207[0m'), and passed after restoration

Upstream: https://github.com/bodil/im-rs

Candidate: 41d9972538d49ffa3964e3a94109619ce053ef36-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 468 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
