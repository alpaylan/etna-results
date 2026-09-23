# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`
  left: `"\"\\xFF\xEF\xBF\xBD\\xFF\""`,
 right: `"\"\\xFF\\xEF\\xBF\\xBD\\xFF\""`'), and passed after restoration

Upstream: https://github.com/BurntSushi/bstr

Candidate: eafb4951c651c4b4eab94621c259f80b217803ee-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 87 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
