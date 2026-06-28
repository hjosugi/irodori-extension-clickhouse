# Native Source

The initial source snapshot was copied from `db/clickhouse.rs` in the desktop app.

Source SHA-256: `91bf9f5fdbb89085987e6480750302e3f25cb0acb9c0734cdaf4c961366f2b79`.


This directory is a migration staging area for `irodori.clickhouse`. The active native
ABI shim lives in `src/lib.rs`; engine-specific connect/query/metadata behavior
should move here as the connector runtime contract is wired into the desktop app.

Engine status from `knowledge/engines.json`: `wired`.
