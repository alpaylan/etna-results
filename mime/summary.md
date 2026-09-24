# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`
  left: `"text/event-stream;"`,
 right: `"text/event-stream"`: case = "text/event-stream;"'), and passed after restoration

Upstream: https://github.com/hyperium/mime

Candidate: 7a39824f8eb816496895593ccda418c177ef5756-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 218 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
