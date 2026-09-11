# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T13:26:37.954861+00:00`
- Run ID: `20260911T132635Z`
- Step: `CAPTURE_EXACT_LIBRARY_ROWS_FILTER`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXACT_LIBRARY_ROWS_FILTER_CAPTURED`
- Next gate: `PATCH_ONLY_TYS_LIBRARY_ROWS_SOURCE_PATH`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `L100`: `and_profit_factor_is_not_None`
- `L46`: `source_sha256,`
- `L51`: `for_row_in_conn.execute(`
- `L53`: `SELECT_candidate_id`
- `L54`: `FROM_candidates`
- `L55`: `WHERE_source_sha256=`
- `L56`: `ORDER_BY_updated_epoch_ms_DESC`
- `L58`: `(source_sha256,),`
- `L64`: `#_Historical_fallback_retained_only_for_resolving`
- `L65`: `#_a_library_script_to_its_candidate_id.`
- `L68`: `for_row_in_conn.execute(`
- `L70`: `SELECT_candidate_id`
- `L71`: `FROM_candidates`
- `L72`: `WHERE_source_url=`
- `L73`: `ORDER_BY_updated_epoch_ms_DESC`
- `L90`: `def__absolute_status(`
- `L91`: `test_status,`
- `L95`: `if_test_status_==_PASS:`
- `L99`: `and_net_return_pct_&gt;_0`
- `RESTART`: `NO`
- `SOURCE_CHANGE`: `NO`
