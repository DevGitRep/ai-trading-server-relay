# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T09:10:02.588397+00:00`
- Run ID: `20260911T091000Z`
- Step: `TRACE_TYS_TO_PIPELINE_RUN_IDENTIFIER`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `TYS_TO_PIPELINE_RUN_IDENTIFIER_CHAIN_FOUND`
- Next gate: `MAP_EXACT_REVIEW_METRIC_JOIN_FROM_EXISTING_CHAIN`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CANDIDATES_COLS`: `candidate_id,created_epoch_ms,updated_epoch_ms,intake_method,name,family,target_market,timeframes_json,source_url,source_author,source_license,source_sha256,pine_version,pine_source,status,discovery_status,causality_status,repaint`
- `CANDIDATE_ROW_MATCH`: `YES`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `FIRST_HOP_MATCH_COUNT`: `4`
- `HOP1_1`: `TYS.candidate_id,CANDIDATE.candidate_id-&gt;pipeline_indicators.indicator_id:indicator_id=ICL_SRC_0F466577DEE17F9F`
- `HOP1_2`: `TYS.candidate_id,CANDIDATE.candidate_id-&gt;pipeline_indicator_versions.indicator_id:indicator_id=ICL_SRC_0F466577DEE17F9F,version_id=IV_0A03674922D94D1616AD`
- `HOP1_3`: `TYS.benchtest_run_id-&gt;pipeline_benchtest_runs.benchtest_run_id:indicator_id=ICL_SRC_0F466577DEE17F9F,version_id=IV_0A03674922D94D1616AD,benchtest_run_id=BTR_AB093E38395F42AF9EB1`
- `HOP1_4`: `TYS.candidate_id,CANDIDATE.candidate_id-&gt;pipeline_benchtest_runs.indicator_id:indicator_id=ICL_SRC_0F466577DEE17F9F,version_id=IV_0A03674922D94D1616AD,benchtest_run_id=BTR_AB093E38395F42AF9EB1`
- `HOP2_1`: `pipeline_indicator_versions.version_id,pipeline_benchtest_runs.version_id,pipeli-&gt;pipeline_indicator_versions.version_id:indicator_id=ICL_SRC_0F466577DEE17F9F,version_id=IV_0A03674922D94D1616AD`
- `HOP2_2`: `TYS.candidate_id,CANDIDATE.candidate_id,pipeline_indicators.indicator_id,pipelin-&gt;pipeline_indicator_versions.indicator_id:indicator_id=ICL_SRC_0F466577DEE17F9F,version_id=IV_0A03674922D94D1616AD`
- `HOP2_3`: `TYS.benchtest_run_id,pipeline_benchtest_runs.benchtest_run_id,pipeline_benchtest-&gt;pipeline_benchtest_runs.benchtest_run_id:indicator_id=ICL_SRC_0F466577DEE17F9F,version_id=IV_0A03674922D94D1616AD,benchtest_run_id=BTR_AB093E38395F42AF9EB1`
- `HOP2_4`: `TYS.candidate_id,CANDIDATE.candidate_id,pipeline_indicators.indicator_id,pipelin-&gt;pipeline_benchtest_runs.indicator_id:indicator_id=ICL_SRC_0F466577DEE17F9F,version_id=IV_0A03674922D94D1616AD,benchtest_run_id=BTR_AB093E38395F42AF9EB1`
- `HOP2_5`: `pipeline_indicator_versions.version_id,pipeline_benchtest_runs.version_id,pipeli-&gt;pipeline_benchtest_runs.version_id:indicator_id=ICL_SRC_0F466577DEE17F9F,version_id=IV_0A03674922D94D1616AD,benchtest_run_id=BTR_AB093E38395F42AF9EB1`
- `INDICATOR_PIPELINE_CURRENT_COLS`: `NONE`
- `PIPELINE_BENCHTEST_RUNS_COLS`: `benchtest_run_id,indicator_id,version_id,preflight_run_id,benchtest_contract,score_method,status,primary_benchmark_mode,primary_profit_factor,primary_net_return_pct,primary_max_drawdown_pct,primary_win_rate_pct,primary_trade_count`
- `PIPELINE_CURRENT_MATCH`: `NO`
- `PIPELINE_INDICATORS_COLS`: `indicator_id,legacy_candidate_id,name,author,source_url,created_at,migrated_at,legacy_snapshot_json`
- `PIPELINE_INDICATOR_MATCH`: `YES`
- `PIPELINE_INDICATOR_VERSIONS_COLS`: `version_id,indicator_id,version_no,script_sha256,script_text,source_kind,source_column,created_at,migrated_at,is_current`
- `PIPELINE_RUN_MATCH`: `YES`
- `PIPELINE_VERSION_MATCH`: `YES`
- `RESTART`: `NO`
- `SECOND_HOP_MATCH_COUNT`: `5`
- `SOURCE_CHANGE`: `NO`
- `TEST_YOUR_SCRIPT_SUBMISSIONS_V1_COLS`: `submission_id,candidate_id,source_sha256,email,rights_confirmed,library_review_allowed,library_publication_status,preexisting_public,technical_status,created_epoch_ms,updated_epoch_ms,benchtest_status,benchtest_started_epoch_ms,be`
- `TYS_CANDIDATE_ID_PRESENT`: `YES`
- `TYS_SOURCE_SHA_PRESENT`: `YES`
- `TYS_SUBMISSION_ID_PRESENT`: `YES`
