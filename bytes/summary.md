# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`
  left: `b""`,
 right: `[104, 101, 108, 108, 111, 119, 111, 114, 108, 100]`'), and passed after restoration

Upstream: https://github.com/tokio-rs/bytes

Candidate: af606aab9be1dde2aeefc1a21344a79beaba7bbe-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 330 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
