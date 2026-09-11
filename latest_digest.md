# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T10:13:45.423993+00:00`
- Run ID: `20260911T101343Z`
- Step: `TRACE_CANONICAL_HELPER_EXCLUSION_CONDITION`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CANONICAL_HELPER_EXCLUDES_NULL_SCORE_TYS_BEFORE_RAW_RESULT`
- Next gate: `IDENTIFY_MINIMAL_REVIEW_ONLY_RAW_RESULT_REUSE_PATH`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `IF1`: `792:_secondary_id_not_in_metrics_map`
- `IF2`: `819:isinstance(_secondary_metric,_dict)`
- `IF3`: `928:_metrics.get(trade_count)_is_None_and__primary_trades_is_not_None`
- `LATEST_TYS_RAW_RESULT_PRESENT`: `YES`
- `LATEST_TYS_REALISTIC_SCORE_NULL`: `YES`
- `MAP1`: `745:metrics_map_=_{}`
- `MAP2`: `764:metrics_=_dict(metrics_map.get(candidate_id)_or_{})`
- `MAP3`: `776:metrics_map[candidate_id]_=_metrics`
- `MAP4`: `814:metrics_map[_secondary_id][_secondary_win_rate_pct_]_=__secondary_value`
- `MAP5`: `852:_metrics_=_metrics_map.get(__profile_id_)`
- `MAP_OP_COUNT`: `5`
- `RAW_PATH_CHECKS_EXISTING_MAP`: `YES`
- `RAW_RESULT_CAN_CREATE_MAP_ENTRY`: `NO`
- `REALISTIC_SCORE_NOT_NULL_FILTER`: `YES`
- `RELEVANT_IF_COUNT`: `3`
- `RELEVANT_LOOP_COUNT`: `4`
- `RESTART`: `NO`
- `SOURCE_CHANGE`: `NO`
- `SQL1`: `748:SELECT_indicator_id,_realistic_score,_primary_profit_factor,_primary_net_return_pct,_primary_max_drawdown_pct,_primary_win_rate_pct,_primary_trade_cou`
- `SQL2`: `782:SELECT_indicator_id,_raw_result_json_FROM_pipeline_benchtest_runs_WHERE_is_current=1`
- `SQL3`: `830:SELECT_p.indicator_id,_p.version_id,_v.script_text,_b.raw_result_json_FROM_indicator_pipeline_current_p_JOIN_pipeline_indicator_versions_v_ON_v.versio`
- `SQL_COUNT`: `3`
