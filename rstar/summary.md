# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion `left == right` failed
  left: AABB { lower: (1.0, 1.0, 1.0), upper: (4.0, 4.0, 4.0) }
 right: AABB { lower: (3.0, 3.0, 3.0), upper: (4.0, 4.0, 4.0) }'), and passed after restoration

Upstream: https://github.com/georust/rstar

Candidate: 7634435cc268b798973f4a81a09f5352382da0fa-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 279 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
