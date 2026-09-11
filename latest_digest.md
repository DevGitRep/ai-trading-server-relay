# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T08:16:51.111710+00:00`
- Run ID: `20260911T081649Z`
- Step: `INSPECT_EXISTING_PUBLIC_SHA_FILTER_SEMANTICS`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `FILTER_APPROVAL_SOURCE_DEPENDENCY_IDENTIFIED`
- Next gate: `VERIFY_EXISTING_APPROVAL_SOURCE_STATE`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `DEP1`: `_connect:FUNCTION:28:def__connect(readonly=False):_if_readonly:_con_=_sqlite3.connect(&#x27;file:&#x27;_+_str(DB)_+_&#x27;mode=ro&#x27;,_uri=True,_timeout=30)_else:_con_=_sqlite3.co`
- `DEP2`: `_policy_map:FUNCTION:46:def__policy_map(con):_if_not__table_exists(con,_POLICY):_return_{}_return_{str(row[&#x27;source_sha256&#x27;]):_{&#x27;status&#x27;:_str(row[&#x27;library_publicatio`
- `EXISTING_LIBRARY_FILTER_CALLS`: `YES`
- `FILTER_ARGS`: `shas`
- `FILTER_CALLS`: `_connect__policy_map_add_close_get_set_str`
- `FILTER_GLOBALS`: `_connect__policy_map_sha`
- `FILTER_HAS_APPROVED_COMPARE`: `YES`
- `FILTER_IF_COUNT`: `3`
- `FILTER_RETURNS_INPUT_SUBSET`: `NO`
- `FILTER_RETURN_COUNT`: `2`
- `IF1`: `not_shas`
- `IF2`: `policy_is_None`
- `IF3`: `policy[&#x27;protect&#x27;]_or_policy[&#x27;status&#x27;]_==_&#x27;APPROVED&#x27;`
- `PREVIOUS_APPROVAL_PATCH_APPLIED`: `NO`
- `RESTART`: `NO`
- `RETURN1`: `result`
- `RETURN2`: `set()`
- `SOURCE_CHANGE`: `NO`
