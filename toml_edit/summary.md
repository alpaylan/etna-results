# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('Parse error: TOML parse error at line 1, column 18
  |
1 | foo = 1979-05-27 # Comment
  |                  ^
Unexpected `#`
expected 2 more elements
While parsing a Date-Time

Failed to parse:
```
foo = 1979-05-27 # Comment

```'), and passed after restoration

Upstream: https://github.com/toml-rs/toml

Candidate: ab0f1041c3469bfbc41459b46ee90173b434d067-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 412 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
