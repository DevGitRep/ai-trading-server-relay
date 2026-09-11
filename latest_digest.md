# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T09:59:21.644080+00:00`
- Run ID: `20260911T095919Z`
- Step: `TRACE_CANONICAL_METRIC_MAP_KEY_FOR_LATEST_CANDIDATE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `LATEST_TYS_EXCLUDED_FROM_CANONICAL_METRIC_MAP`
- Next gate: `TRACE_ONLY_CANONICAL_HELPER_EXCLUSION_CONDITION`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CANDIDATE_ROW_PRESENT`: `YES`
- `CLOUDFLARE_ACTION`: `NO`
- `CURRENT_PROFIT_FACTOR`: `NULL`
- `CURRENT_REALISTIC_SCORE`: `NULL`
- `DB_WRITE`: `NO`
- `HELPER_TERMS`: `candidate_id,indicator_id,is_current,realistic_score,raw_result_json,indicator_pipeline_current,pipeline_benchtest_runs`
- `MAP_ASSIGN1`: `745:metrics_map_=_{}`
- `MAP_ASSIGN2`: `764:metrics_=_dict(metrics_map.get(candidate_id)_or_{})`
- `MAP_ASSIGN3`: `776:metrics_map[candidate_id]_=_metrics`
- `MAP_ASSIGN4`: `814:metrics_map[_secondary_id][_secondary_win_rate_pct_]_=__secondary_value`
- `MAP_ASSIGNMENT_COUNT`: `5`
- `MAP_HAS_CANDIDATE_ID`: `NO`
- `MAP_HAS_INDICATOR_ID`: `NO`
- `MAP_HAS_SOURCE_SHA`: `NO`
- `MAP_HAS_SUBMISSION_ID`: `NO`
- `MAP_HAS_VERSION_ID`: `NO`
- `METRIC_MAP_SIZE`: `16`
- `PIPELINE_CURRENT_PRESENT`: `YES`
- `PIPELINE_INDICATOR_PRESENT`: `YES`
- `PIPELINE_RUN_PRESENT`: `YES`
- `PIPELINE_VERSION_PRESENT`: `YES`
- `RESTART`: `NO`
- `RUN_IS_CURRENT`: `1`
- `RUN_RAW_RESULT`: `YES`
- `SOURCE_CHANGE`: `NO`
- `TYS_CANDIDATE_PRESENT`: `YES`
