# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T09:48:57.337567+00:00`
- Run ID: `20260911T094855Z`
- Step: `MAP_REVIEW_CONNECTION_LIFECYCLE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CANONICAL_METRIC_CALL_OCCURS_AFTER_CONNECTION_CLOSE`
- Next gate: `MOVE_ONLY_METRIC_MAP_CALL_BEFORE_CON_CLOSE`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CALL1`: `61:execute`
- `CALL2`: `114:execute`
- `CALL3`: `129:execute`
- `CALL4`: `151:execute`
- `CALL5`: `221:close`
- `CALL6`: `251:_bulk_pipeline_metrics_v1`
- `CLOSE_BEFORE_HELPER`: `YES`
- `CLOUDFLARE_ACTION`: `NO`
- `CON_CLOSE_LINES`: `221`
- `DB_WRITE`: `NO`
- `ERROR_CAUSE`: `CLOSED_DATABASE`
- `ERROR_TYPE`: `ProgrammingError`
- `HELPER_CALL_LINES`: `251`
- `PATCH_MARKER_LINE`: `249`
- `RENDER_LOOP_LINE`: `252`
- `RESTART`: `NO`
- `ROWS_ASSIGN_LINE`: `151`
- `SOURCE_CHANGE`: `NO`
