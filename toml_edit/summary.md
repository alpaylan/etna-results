# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`

[1mDiff[0m [31m< left[0m / [32mright >[0m :
 
 [tbl]
 key1 = "value1"
 key2 = 42
[31m<key3 = 8.1415926[0m
[32m>key3 = 8.1415926[0m[1;48;5;22;32me0[0m
 
         [tbl.son]'), and passed after restoration

Upstream: https://github.com/toml-rs/toml

Candidate: c8713e0aed0210ca8beecd4a5a0a61f2b7f3809a-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 310 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
