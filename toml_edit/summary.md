# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`

[1mDiff[0m [31m< left[0m / [32mright >[0m :
 
 [nixpkgs]
[31m<src[0m[1;48;5;52;31m.[0m[31mgit = "https://github.com/nixos/nixpkgs"[0m
[32m>src[0m[1;48;5;22;32m = { [0m[32mgit = "https://github.com/nixos/nixpkgs"[0m[1;48;5;22;32m}[0m'), and passed after restoration

Upstream: https://github.com/toml-rs/toml

Candidate: 31e0b124d70db6254309a6db6ea3927ec858fb2c-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 370 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
