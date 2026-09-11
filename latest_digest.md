# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T09:51:10.532228+00:00`
- Run ID: `20260911T095108Z`
- Step: `INSPECT_EXACT_REVIEW_METRIC_BLOCK`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXACT_METRIC_CALL_AND_CLOSE_LOCATED`
- Next gate: `MOVE_ONLY_EXISTING_HELPER_CALL_BEFORE_CLOSE`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `CON_CLOSE_LINE`: `221`
- `DB_WRITE`: `NO`
- `HELPER_AFTER_CLOSE`: `YES`
- `HELPER_CALL_LINE`: `251`
- `IMPORT_LINE`: `250`
- `LINE1`: `221:INDENT12:_con.close()`
- `LINE2`: `249:INDENT8:__INTERNAL_REVIEW_CANONICAL_METRICS_V1`
- `LINE3`: `250:INDENT8:_from_indicator_lab_library_ui_v1_import__bulk_pipeline_metrics_v1`
- `LINE4`: `251:INDENT8:__canonical_metrics_map_=__bulk_pipeline_metrics_v1(con)`
- `LINE5`: `252:INDENT8:_for_r_in_rows:`
- `LINE6`: `253:INDENT12:__INTERNAL_REVIEW_CANONICAL_METRICS_V1_ROW`
- `LINE7`: `254:INDENT12:__canonical_metrics_=__canonical_metrics_map.get(`
- `LINE8`: `405:INDENT0:{%_for_r_in_rows_%}`
- `MARKER_LINE`: `249`
- `RELEVANT_LINE_COUNT`: `8`
- `RESTART`: `NO`
- `SOURCE_CHANGE`: `NO`
