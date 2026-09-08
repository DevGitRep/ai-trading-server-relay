# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T08:26:50.241739+00:00`
- Run ID: `20260908T082647Z`
- Step: `TRACETRADELINKV2`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `TRADELINKTRACED`
- Next gate: `PATCHREPORTV2`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `CANON_RUN`: `BTR_21BD506A81130BD4B893`
- `CANON_TIME`: `20260907T091202Z`
- `DB_WRITE`: `NO`
- `GROUPS`: `d459deaf-d9b0-4a06-a842-2ad5507a1b0b:21:1-21`
- `LINK_HITS`: `benchtest_trades_v1:21`
- `LINK_TABLES`: `benchtest_trades_v1,default_test_results_v1,default_test_trades_v1,pine_baseline_leaderboard_v1,pine_baseline_thumbnails_v1,pine_library_discovery_ran`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `OLD_QUERY`: `con.execute( &quot;&quot;&quot; SELECT trade_no, candidate_id, raw_json FROM benchtest_trades_v1 WHERE run_id=? ORDER BY CAST(trade_no AS INTEGER) LIMIT 5000 &quot;&quot;&quot;, ( run_id, ), ).fetchall()`
- `PREFLIGHT_RERUN`: `NO`
- `QUICK`: `ok`
- `RAW_RUNS`: `run_id=d459deaf-d9b0-4a06-a842-2ad5507a1b0b`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
