# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`

[1mDiff[0m [31m< left[0m / [32mright >[0m :
 
         [package]
         [dependencies]
[31m<        [[example]][0m
         [dependencies.opencl]
 
 [dependencies.newthing]
[32m>        [[example]][0m
         [dev-dependencies]'), and passed after restoration

Upstream: https://github.com/toml-rs/toml

Candidate: a7e1daf8df7e11a999ae22f577cdf2446c2abd3f-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 289 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
