# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`

[1mDiff[0m [31m< left[0m / [32mright >[0m :
 [
     (
         1,
         2,
     ),
     (
         2,
         3,
     ),
     (
         3,
         4,
     ),
     (
         4,
         5,
     ),
     (
         5,
         6,
     ),
[32m>    (
[0m[32m>        7,
[0m[32m>        8,
[0m[32m>    ),
[0m ]'), and passed after restoration

Upstream: https://github.com/bodil/im-rs

Candidate: 3f4e01a43254fe228d1ce64e47dfaf4edc8f4f19-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 466 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
