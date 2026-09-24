# Cloud bug-mining prototype

Resumed verified evidence; no tests rerun.

**confirmed**: The same upstream test passed, panicked on the original defect ('called `Result::unwrap()` on an `Err` value: Error(Deserialize { pos: None, err: DeserializeError { field: Some(1), kind: InvalidUtf8(Utf8Error { valid_up_to: 3, error_len: Some(1) }) } })'), and passed after restoration

Upstream: https://github.com/BurntSushi/rust-csv

Candidate: 9e644e66db0aa0b931758de1c2b7da555fb632b7-1

Provenance: verbatim

Latest outcomes: {"confirmed": 1}

Reviewed commits: 1 / 372 reachable from the saved tip.

Scope: one queued candidate; history coverage is partial.
