# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-07T11:26:31.133836+00:00`
- Run ID: `20260907T112629Z`
- Step: `READLIBRARYBULKLOOKUP`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `LIBRARYROWIDAVAILABLEBUTLOOKUPNEEDSONEPATCH`
- Next gate: `PATCHBULKMAPANDLOOKUPTOCANDIDATEID`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `BULKKEY`: `candidate_id`
- `BULKRETURNS`: `1`
- `BULKSQL`: `conn.execute( &quot;&quot;&quot; SELECT candidate_id, signal_mode, test_status, net_return_pct, max_drawdown_pct, p`
- `BULKSQLN`: `1`
- `BULKVAR`: `bench_metrics_map`
- `CHANGES_MADE`: `NO`
- `COMPLETE`: `16`
- `DB_WRITE`: `NO`
- `IDCAND`: `NO`
- `IDEXPR`: `NONE`
- `IDEXPRN`: `0`
- `LOOKUPKEY`: `UNRESOLVED`
- `LOOKUPN`: `0`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `QUICK`: `ok`
- `RESTART`: `NO`
- `ROWSQL`: `_bench_v31ae_con.execute( &quot;&quot;&quot; SELECT b.candidate_id, b.&quot;profit_factor&quot; AS _profit_factor, b.&quot;net_ret`
- `ROWSQLN`: `2`
- `SCORED`: `16`
- `SOURCE_CHANGE`: `NO`
- `VIEWROWS`: `11775`
