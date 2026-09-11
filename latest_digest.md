# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T10:57:50.743993+00:00`
- Run ID: `20260911T105748Z`
- Step: `TRACE_VALUES_PAYLOAD_BEFORE_PIPELINE_WRITER`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `VALUES_IS_CALLSITE_FUNCTION_ARGUMENT`
- Next gate: `TRACE_CALLER_THAT_BUILDS_VALUES_PAYLOAD`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CALLSITE_FUNCTION`: `_v2_insert_result`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `FUNCTION_ARGS`: `con,values`
- `METRIC_KEY_OP_COUNT`: `0`
- `RESTART`: `NO`
- `SOURCE_CHANGE`: `NO`
- `VALUES_IS_FUNCTION_ARG`: `YES`
- `VALUES_OP1`: `L3671:CALL:_v2_pipeline_insert_result_v1(con,_values)`
- `VALUES_OP_COUNT`: `1`
