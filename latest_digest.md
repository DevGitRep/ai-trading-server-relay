# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T12:07:31.591994+00:00`
- Run ID: `20260911T120729Z`
- Step: `MAP_EXACT_CHECKBOX_DISABLE_CONDITION`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CHECKBOX_DISABLE_CONDITION_LOCATED`
- Next gate: `PATCH_ONLY_VALID_REVIEW_ROW_ENABLE_CONDITION`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `DISABLED_EXPR_PRESENT`: `YES`
- `LINE1`: `296:approved:_(`
- `LINE10`: `433:type=checkbox`
- `LINE11`: `434:name=approved`
- `LINE12`: `436:{%_if_r.approved_%}checked{%_endif_%}`
- `LINE13`: `437:{%_if_not_r.ready_%}disabled{%_endif_%}`
- `LINE14`: `438:onchange=this.form.submit()`
- `LINE2`: `298:r[publication_status]`
- `LINE3`: `301:==_APPROVED`
- `LINE4`: `421:&lt;form_method=post&gt;`
- `LINE5`: `422:&lt;input`
- `LINE6`: `424:name=submission_id`
- `LINE7`: `427:&lt;input`
- `LINE8`: `429:name=approved`
- `LINE9`: `432:&lt;input`
- `RELEVANT_LINE_COUNT`: `14`
- `RESTART`: `NO`
- `REVIEW_ALLOWED_REFERENCE`: `NO`
- `SOURCE_CHANGE`: `NO`
