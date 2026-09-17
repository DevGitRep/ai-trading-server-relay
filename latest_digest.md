# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-17T08:02:17.720769+00:00`
- Run ID: `20260917T080215Z`
- Step: `MAP_EXACT_PINER_RAW_OUTPUT_TO_SELECTION_SEAM`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `PINER_SELECTION_INTERNAL_SEAM_MAPPED`
- Next gate: `RUN_PINER_RAW_PRESELECTION_OUTPUT_ON_REAL_SOL_YEAR_AND_MATCH_PREFLIGHT_HYPOTHESIS`

## Facts

- `ATB_CHANGED`: `NO`
- `CALLS`: `120:obj.get,139:str,140:str,141:list,142:list,171:str,94:PINER_CONTRACT.exists,98:subprocess.run,111:json.loads,`
- `DASHBOARD_RESTART`: `NO`
- `DB_WRITES`: `0`
- `FAILURE`: `NONE`
- `INTERNAL_RC`: `0`
- `JSON_CALLS`: `json.loads(proc.stdout_or_{})`
- `KEY_ASSIGNMENTS`: `contracts=[],contract_id=str(selected.get(contract_id)_or_ctype)`
- `LOOPS`: `contract_in_obj.get(contracts,_[]),key_in_(_title,_message,_series,_series_a,_series_b,_threshold,_level_)`
- `PRESELECTION_LIST_FOUND`: `YES`
- `RAW_COLLECTION`: `contracts`
- `READ_ONLY`: `YES`
- `RETURNS`: `{_lane:_LANE_BY_TYPE[ctype],_expressions:_expressions,_evidence:_evidence,_author_label:_label,_priority:_TYPE_P`
- `SELECTION_EXPR`: `{_lane:_LANE_BY_TYPE[ctype],_expressions:_expressions,_evidence:_evidence,_author_label:_label,_priority:_TYPE_P`
- `SIGNATURE`: `select_piner_candidate(source,candles)`
- `SORTS`: `sorted(contracts,_key=_sort_key)`
- `SUBPROCESS_CALL`: `subprocess.run(_[node,_str(PINER_CONTRACT)],_cwd=PINER_ROOT,_input=json.dumps({_source:_source,_candles:__candle`
- `YEAR_RESELECTION`: `NO`
