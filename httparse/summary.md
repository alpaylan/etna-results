# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`
  left: `Ok(Complete(77))`,
 right: `Err(HeaderName)`'), and passed after restoration

Upstream: https://github.com/seanmonstar/httparse

Candidate: 7ab01920b151a121ac81dc7a30a7c82c4d99480c-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 175 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
