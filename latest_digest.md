# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-08-30T20:14:11.242447+00:00`
- Run ID: `20260830T201409Z`
- Step: `READ_FULL_SELECT_UNTESTED_FLOW`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `SELECT_UNTESTED_FULL_FLOW_READ`
- Next gate: `USE_REPORTED_FLOW_ONLY`

## Facts

- `ATTEMPT_LITERAL_IN_FN`: `NO`
- `CANDIDATES_REF_IN_FN`: `NO`
- `CODE_CHANGED`: `NO`
- `COUNT_USED_IN_FN`: `YES`
- `DB_WRITE`: `NO`
- `ERROR`: `NONE`
- `FUNCTION_FOUND`: `YES`
- `HELPER_CALLS`: `fail,conn.commit,hexdigest,already_tested,ensure_candidate,selected.append,hashlib.sha256,source.enc`
- `MASTER_UPDATED`: `NO`
- `ORDER_USED_IN_FN`: `YES`
- `POPULAR_LITERAL`: `NO`
- `RECENT_LITERAL`: `YES`
- `RETURN_ASSIGN_CALL`: `NONE`
- `RETURN_ASSIGN_LINE`: `214`
- `RETURN_ASSIGN_TYPE`: `List`
- `RETURN_NAME`: `selected`
- `SCRIPTS_REF_IN_FN`: `YES`
- `SOURCES_REF_IN_FN`: `YES`
- `SQL1`: `SELECT:scripts:ORDER,LIMIT`
- `SQL2`: `NONE`
- `SQL3`: `NONE`
- `SQL4`: `NONE`
- `SQL_COUNT`: `1`
