# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`

[1mDiff[0m [31m< left[0m / [32mright >[0m :
[31m<"1987-07-05T17:45:00"[0m
[32m>"1987-07-05T17:45:00[0m[1;48;5;22;32m.123456789012345Z[0m[32m"[0m'), and passed after restoration

Upstream: https://github.com/toml-rs/toml

Candidate: 9e81c5a9e380f06bddee7e26ccec70e95acdb4a5-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 411 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
