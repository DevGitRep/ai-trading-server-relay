# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-12T13:58:08.286477+00:00`
- Run ID: `20260912T135806Z`
- Step: `FREEPROFILERUNTIME`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `PROVIDER_RETURNS_PROFILE_VALUES`
- Next gate: `APPLY_MINIMAL_FIX_AT_CONFIRMED_FAILURE_POINT`

## Facts

- `CANDIDATES`: `8`
- `NONEMPTY`: `8`
- `RUNTIME01`: `table=benchtest_trades_v1;cid=ICL_LIB_BAE7213D641A93F1;;keys=trade_count=None`
- `RUNTIME02`: `table=candidate_events;cid=ICL_SRC_A465DEED5818C8FA;;keys=trade_count=None`
- `RUNTIME03`: `table=candidate_events;cid=ICL_SRC_0F466577DEE17F9F;;keys=trade_count=None`
- `RUNTIME04`: `table=candidate_events;cid=ICL_SRC_CEC9B86A38AB67BC;;keys=trade_count=None`
- `RUNTIME05`: `table=candidate_events;cid=ICL_SRC_5DDF4CA66408AD45;;keys=trade_count=None`
- `RUNTIME06`: `table=candidate_events;cid=ICL_SRC_E558340012BC5889;;keys=trade_count=None`
- `RUNTIME07`: `table=candidate_events;cid=ICL_SRC_84D48D4BBE82B9E8;;keys=trade_count=None`
- `RUNTIME08`: `table=candidates;cid=ICL_LIB_3D53BEDC9DE5F7C5;status=LIBRARY_READY,discovery_status=NOT_STARTED,causality_status=PENDING;keys=trade_count=None`
- `SOURCE01`: `L1547:row = conn.execute(f&quot;\n SELECT\n s.chart_url,\n so.source,\n {signal_role},\n {signal_role_reason},\n {signal_role_updated_at}\n\n FROM scripts s\n\n JOIN sources so\n ON so.rowid`
- `SOURCE02`: `L1554:candidate_ids = _candidate_ids(conn, sha, row[&#x27;chart_url&#x27;])`
- `SOURCE03`: `L1555:metrics = _best_metrics_from_map(candidate_ids, _bulk_pipeline_metrics_v1(conn)) or _empty_metrics()`
- `SOURCE04`: `L1565:# excluded from the returned FREE projection.`
