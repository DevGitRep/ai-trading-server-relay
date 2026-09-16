# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-16T18:49:14.659167+00:00`
- Run ID: `20260916T184912Z`
- Step: `TRACE_EXACT_PREFLIGHT_COUNT_QUERY`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXACT_PREFLIGHT_COUNT_QUERY_MAPPED`
- Next gate: `RESET_ONLY_EXACT_PREFLIGHT_STORAGE`

## Facts

- `CALLER`: `indicator_library_ui_v2_stats`
- `CON_1`: `15157:con=sqlite3.connect(`
- `CON_2`: `NONE`
- `CON_3`: `NONE`
- `CON_4`: `NONE`
- `DB_WRITES`: `0`
- `FAILURE`: `NONE`
- `HELPER_SIG`: `con,_tables,_current_shas`
- `INTERNAL_RC`: `0`
- `READ_ONLY`: `YES`
- `RETURN`: `(0,_0,_&#x27;NO_PROVEN_PREFLIGHT_MARKER&#x27;)`
- `SHAS_1`: `15173:current_shas=(`
- `SHAS_2`: `15187:current_shas,`
- `SHAS_3`: `15196:current_shas,`
- `SHAS_4`: `15203:len(current_shas),`
- `SQL_1`: `con.execute(&#x27;SELECT_&#x27;_+__indicator_library_ui_v2_q(identity)_+_&#x27;,notes_FROM_candidates_&#x27;_+_&#x27;WHERE_notes_LIKE_&#x27;,_(&#x27;TESTPINE_PREFLIGHT_V1=&#x27;,)).fetchall()`
- `SQL_2`: `con.execute(&#x27;SELECT_&#x27;_+__indicator_library_ui_v2_q(identity)_+_&#x27;,notes_FROM_candidates_&#x27;_+_&#x27;WHERE_notes_LIKE_&#x27;,_(&#x27;TESTPINE_PREFLIGHT_V1=&#x27;,))`
- `SQL_3`: `WHERE_notes_LIKE_`
- `SQL_4`: `,notes_FROM_candidates`
- `SQL_5`: `SELECT`
- `SQL_6`: `NONE`
- `SQL_7`: `NONE`
- `SQL_8`: `NONE`
- `TABLES_1`: `15165:tables=`
- `TABLES_2`: `NONE`
- `TABLES_3`: `NONE`
- `TABLES_4`: `NONE`
- `TABLE_REF_1`: `NONE`
- `TABLE_REF_2`: `NONE`
- `TABLE_REF_3`: `NONE`
- `TABLE_REF_4`: `NONE`
- `TABLE_REF_5`: `NONE`
- `TABLE_REF_6`: `NONE`
