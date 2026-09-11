# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T09:17:20.203684+00:00`
- Run ID: `20260911T091718Z`
- Step: `TRACE_CANONICAL_PIPELINE_METRIC_SOURCE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `REVIEW_MISSING_CANONICAL_RAW_RESULT_METRIC_EXTRACTION`
- Next gate: `PATCH_REVIEW_TO_REUSE_CANONICAL_METRIC_EXTRACTION_ONLY`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CANONICAL_METRIC_TERMS`: `primary_profit_factor,primary_trade_count,primary_win_rate_pct,secondary_win_rate_pct,primary_net_return_pct,primary_max_drawdown_pct,profit_factor,trade_count,win_rate_pct,net_return_pct,max_drawdown_pct,raw_result_json,indicator`
- `CANONICAL_SQL1`: `SELECT_indicator_id,_realistic_score,_primary_profit_factor,_primary_net_return_pct,_primary_max_drawdown_pct,_primary_win_rate_pct,_primary_trade_count_FROM_indicator_pipeline_current_WHERE_realistic_score_IS_NOT_NULL`
- `CANONICAL_SQL2`: `SELECT_indicator_id,_raw_result_json_FROM_pipeline_benchtest_runs_WHERE_is_current=1`
- `CANONICAL_SQL3`: `SELECT_p.indicator_id,_p.version_id,_v.script_text,_b.raw_result_json_FROM_indicator_pipeline_current_p_JOIN_pipeline_indicator_versions_v_ON_v.version_id_=_p.version_id_JOIN_pipeline_benchtest_runs_b_ON_b.indicator_id_=_p.indicat`
- `CANONICAL_SQL_COUNT`: `3`
- `CANONICAL_USES_RAW_RESULT`: `YES`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `PIPELINE_RUN_COUNT`: `1`
- `RAW_RESULT_METRIC_KEYS`: `NONE`
- `RESTART`: `NO`
- `REVIEW_CHAIN_ALREADY_PRESENT`: `YES`
- `REVIEW_USES_RAW_RESULT`: `NO`
- `RUN_NON_NULL_METRIC_FIELDS`: `raw_result_json,score_method`
- `SOURCE_CHANGE`: `NO`
