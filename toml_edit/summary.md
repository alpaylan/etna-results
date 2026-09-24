# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`

[1mDiff[0m [31m< left[0m / [32mright >[0m :
[31m<"\n[table]\n[0m[1;48;5;52;31m [0m[31mstring = \"value\"\n[0m[1;48;5;52;31m [0m[31marray = [1, 2, 3]\n[0m[1;48;5;52;31m [0m[31minline = { \"1\" = 1, \"2\" = 2 }\n[0m[1;48;5;52;31m [0m[31mchild = { other = \"world\" }[0m[1;48;5;52;31m [0m[31m\n"[0m
[32m>"\n[table]\nstring = \"value\"\narray = [1, 2, 3]\ninline = { \"1\" = 1, \"2\" = 2 }\nchild = { other = \"world\" }\n"[0m'), and passed after restoration

Upstream: https://github.com/toml-rs/toml

Candidate: 3105fed18a5b259f3697c5c808586fc06d8005be-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 401 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
