# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`
  left: `BitVec<bitvec::order::Lsb0, u8> { addr: 0x55fb27de6da0, head: 000, bits: 10, capacity: 64 } [00000000, 00]`,
 right: `BitSlice<bitvec::order::Lsb0, usize> { addr: 0x7ffde63dd380, head: 000000, bits: 10 } [0000011111]`'), and passed after restoration

Upstream: https://github.com/ferrilab/bitvec

Candidate: 935cad8888d0f09837b95000c44f4a56579c7108-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 433 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
