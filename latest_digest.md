# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T08:56:06.743846+00:00`
- Run ID: `20260911T085604Z`
- Step: `TRACE_REVIEW_TO_PIPELINE_LINEAGE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `REVIEW_ROWS_NOT_MATCHING_PIPELINE_RUNS`
- Next gate: `TRACE_TYS_TO_PIPELINE_RUN_IDENTIFIER_ONLY`

## Facts

- `ANY_PIPELINE_CURRENT_MATCH`: `NO`
- `ANY_PIPELINE_RUN_MATCH`: `NO`
- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `PIPELINE_CURRENT_COLS`: `NONE`
- `PIPELINE_RUN_COLS`: `benchtest_run_id,indicator_id,version_id,preflight_run_id,benchtest_contract,score_method,status,primary_benchmark_mode,primary_profit_factor,primary_net_return_pct,primary_max_drawdown_pct,primary_win_rate_pct,primary_t`
- `RESTART`: `NO`
- `REVIEW_KEY_TERMS`: `candidate_id,source_sha256,submission_id,run_id,benchtest_run_id,indicator_id,version_id`
- `REVIEW_PIPELINE_SQL1`: `SELECT_t.submission_id,_t.created_epoch_ms,_t.email,_t.technical_status,_t.benchtest_status,_c.name,_c.source_author,_COALESCE(_p.library_publication_status,_t.library_publication_status_)_AS_publication_status,_b.primar`
- `REVIEW_PIPELINE_SQL_COUNT`: `1`
- `ROW1_CURRENT_MATCH`: `NO`
- `ROW1_RUN_MATCH`: `NO`
- `ROW2_CURRENT_MATCH`: `NO`
- `ROW2_RUN_MATCH`: `NO`
- `ROW3_CURRENT_MATCH`: `NO`
- `ROW3_RUN_MATCH`: `NO`
- `ROW4_CURRENT_MATCH`: `NO`
- `ROW4_RUN_MATCH`: `NO`
- `ROW5_CURRENT_MATCH`: `NO`
- `ROW5_RUN_MATCH`: `NO`
- `ROW6_CURRENT_MATCH`: `NO`
- `ROW6_RUN_MATCH`: `NO`
- `ROW7_CURRENT_MATCH`: `NO`
- `ROW7_RUN_MATCH`: `NO`
- `ROW8_CURRENT_MATCH`: `NO`
- `ROW8_RUN_MATCH`: `NO`
- `SOURCE_CHANGE`: `NO`
