# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-23T20:39:55.376613+00:00`
- Run ID: `20260923T203953Z`
- Step: `TRACEBENCHTESTLOOKUPCHAIN`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `BENCHTEST_CANDIDATE_LOOKUP_CHAIN_TRACED`
- Next gate: `QUERY_EXACT_BENCHTEST_SOURCE`

## Facts

- `ARTIFACT_RUN_RHS`: `_payload.get(&#x27;run_id&#x27;)`
- `DASHBOARD_RESTART`: `NO`
- `FILE_DELETES`: `0`
- `GIT_COMMITS`: `0`
- `GIT_PUSHES`: `0`
- `HEAD`: `21ba6c2a65a3`
- `INDICATOR_RHS`: `str(_metrics.get(&#x27;candidate_id&#x27;) or &#x27;&#x27;).strip()`
- `LOCAL_HELPERS`: `0`
- `LOOKUP_ASSIGNMENTS`: `4`
- `METRICS_LINE`: `1931`
- `METRICS_RHS`: `_report_metrics(candidate_id, &#x27;PRO&#x27;)`
- `PRODUCTION_CODE_WRITES`: `0`
- `PRODUCTION_DB_WRITES`: `0`
- `REPO_CLEAN`: `YES`
- `ROUTE_CALLS`: `26`
- `RUN_RHS`: `_con.execute(f&#x27;n SELECTn primary_benchmark_mode,n primary_trade_count,n &quot;{_raw_columns[0]}&quot; AS payloadn FROM pipeline_benchtest_runsn WHERE indicator_id=?n AND is_current=1n LIMIT 1n &#x27;, (_indicator_id,)).fetchone()`
