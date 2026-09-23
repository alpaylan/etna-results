# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion `left == right` failed
  left: "\"\\xff�\\xff\""
 right: "\"\\xFF�\\xFF\""'), and passed after restoration

Upstream: https://github.com/BurntSushi/bstr

Candidate: af99a6ecb4723d0ea03982797a1becd8437d3f7d-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 228 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
