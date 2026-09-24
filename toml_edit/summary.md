# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`

[1mDiff[0m [31m< left[0m / [32mright >[0m :
 
[31m<    a = [1, "2", 3.0][0m
[32m>    a = [1, "2", 3.0,[0m
[32m>    ][0m'), and passed after restoration

Upstream: https://github.com/toml-rs/toml

Candidate: 0140c9369dd70fd92ae2c7cf83f13180e819b806-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 405 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
