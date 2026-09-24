# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('assertion failed: `(left == right)`
  left: `1`,
 right: `0`: failed to find "ab" in "AB"

automaton:
AhoCorasick { imp: NFA(NFA(
match_kind: Standard
-------------------------------------------------------------------------------
0000: 
  matches: 
     fail: 2
    depth: 0
0001: 
  matches: 
     fail: 2
    depth: 0
0002: A => 3, a => 3
  matches: 
     fail: 2
    depth: 0
0003: B => 4, b => 4
  matches: 
     fail: 2
    depth: 1
0004: 
  matches: 0
     fail: 2
    depth: 2
-------------------------------------------------------------------------------
)
), match_kind: Standard }'), and passed after restoration

Upstream: https://github.com/BurntSushi/aho-corasick

Candidate: e9110e994ba784ff9f813660f96d914dfe53207d-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 154 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
