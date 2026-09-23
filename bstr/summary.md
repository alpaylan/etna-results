# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion `left == right` failed
  left: "\"\\0\\x01\\x02\\x03\\x04\\x05\\x06\\x07\\x08\\t\\n\\x11\\x12\\r\\x14\\x15\\x16\\x17\\x18\\x19\\x1a\\x1b\\x1c\\x1d\\x1e\\x1f \\x7f\\x80\\x81\\xfe\\xff\""
 right: "\"\\0\\x01\\x02\\x03\\x04\\x05\\x06\\x07\\x08\\t\\n\\x11\\x12\\r\\x14\\x15\\x16\\x17\\x18\\x19\\u{1a}\\u{1b}\\u{1c}\\u{1d}\\u{1e}\\u{1f} \\x7f\\x80\\x81\\xfe\\xff\""'), and passed after restoration

Upstream: https://github.com/BurntSushi/bstr

Candidate: 732fc99f3844d88dc40f33d95a7bc8f3f6bd2e5b-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 237 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
