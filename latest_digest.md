# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-16T18:53:44.323432+00:00`
- Run ID: `20260916T185342Z`
- Step: `TRACE_LIVE_INDICATOR_LIBRARY_DATABASE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `LIVE_INDICATOR_LIBRARY_DB_PATH_MAPPED`
- Next gate: `RESET_PREFLIGHT_MARKERS_IN_LIVE_DB_ONLY`

## Facts

- `CALLER`: `indicator_library_ui_v2_stats`
- `CONNECT_ARG`: `&#x27;file:&#x27;_+__indicator_library_ui_v2_db()_+_&#x27;mode=ro&#x27;`
- `CONNECT_LINE`: `15157`
- `DB_ASSIGN`: `NONE`
- `DB_ASSIGN_LINE`: `0`
- `DB_SYMBOL`: `NONE`
- `DB_WRITES`: `0`
- `FAILURE`: `NONE`
- `INTERNAL_RC`: `0`
- `READ_ONLY`: `YES`
- `SHAS_ASSIGN`: `_indicator_library_ui_v2_current_executable_shas(con,_tables)`
- `SHAS_LINE`: `15173`
- `TABLES_ASSIGN`: `r[0]_for_r_in_con.execute(&#x27;SELECT_name_FROM_sqlite_master_WHERE_type=&#x27;,_(&#x27;table&#x27;,)).fetchall()`
- `TABLES_LINE`: `15165`
