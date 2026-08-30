# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-08-30T20:15:11.376513+00:00`
- Run ID: `20260830T201509Z`
- Step: `READ_SELECTION_HELPERS_AND_PAYLOAD`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CANONICAL_SELECTION_HELPERS_READ`
- Next gate: `RECONSTRUCT_EXACT_LAST_SELECTION_READ_ONLY`

## Facts

- `ALREADY_CALL_ARGS`: `conn,sha`
- `ALREADY_CALL_FOUND`: `YES`
- `ALREADY_FN_FOUND`: `YES`
- `ALREADY_RETURN`: `row is not None`
- `ALREADY_SQL_MARKER`: `YES`
- `ALREADY_SQL_TABLE`: `candidates`
- `APPEND_FOUND`: `YES`
- `APPEND_KEYS`: `candidate_id,provider,url,source_url,query,script_id_part,source_version`
- `APPEND_VALUE_NAMES`: `candidate_id,&#x27;PINE_LIBRARY&#x27;,&#x27;library:&lt;path&gt;&#x27; + candidate_id,&#x27;library:&lt;path&gt;&#x27; + candidate_id,row[&#x27;nam`
- `CODE_CHANGED`: `NO`
- `DB_WRITE`: `NO`
- `ENSURE_CALL_ARGS`: `conn,row,source,sha`
- `ENSURE_CALL_FOUND`: `YES`
- `ENSURE_COMMITS`: `NO`
- `ENSURE_FN_FOUND`: `YES`
- `ENSURE_READ_TABLE`: `NONE`
- `ENSURE_RETURNS_ID`: `YES`
- `ENSURE_WRITE_TABLE`: `candidates`
- `ERROR`: `NONE`
- `LOOP_TARGET`: `row`
- `MASTER_UPDATED`: `NO`
- `SCRIPT_SQL_LIMIT`: `1`
- `SCRIPT_SQL_ORDER`: `coalesce(x.fetched_at,&#x27;&#x27;) desc, x.rowid desc`
- `SELECT_FN_FOUND`: `YES`
