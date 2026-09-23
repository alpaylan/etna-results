# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`
  left: `"\"\\0\\0\\0 ftypisom\\0\\0\\x02\\0isomiso2avc1mp\""`,
 right: `"\"\\u{0}\\u{0}\\u{0} ftypisom\\u{0}\\u{0}\\u{2}\\u{0}isomiso2avc1mp\""`'), and passed after restoration

Upstream: https://github.com/BurntSushi/bstr

Candidate: 8e2041ed5481078f25635dd7989a96abd87721ce-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 86 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
