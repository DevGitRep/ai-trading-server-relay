# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T08:15:26.954942+00:00`
- Run ID: `20260911T081524Z`
- Step: `TRACE_EXISTING_TYS_PUBLIC_SHA_FILTER`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXISTING_TYS_PUBLIC_SHA_FILTER_FOUND_BUT_APPROVAL_NOT_PROVEN`
- Next gate: `INSPECT_ONLY_FILTER_SEMANTICS`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CALL1`: `1230:_tys_filter_public_shas(__str(itemsource_sha256)_for_item_in_library_rows_if_itemsource_sha256__)`
- `CALL2`: `1325:_tys_filter_public_shas(_list(_fallback_sha_by_pair.values()_)_)`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `DEF1`: `test_your_script_v1.py:filter_public_shas:51:APPROVED`
- `FILTER_BINDS_SHA`: `NO`
- `FILTER_CALL_COUNT`: `2`
- `FILTER_DEF_COUNT`: `1`
- `FILTER_HAS_APPROVED`: `YES`
- `FILTER_HAS_PRIVATE`: `NO`
- `FILTER_ORIGIN_COUNT`: `1`
- `FILTER_READS_POLICY`: `NO`
- `FILTER_READS_TYS`: `NO`
- `FILTER_SQL_COUNT`: `0`
- `LIBRARY_ROWS_FILTER_CALL_EXISTS`: `YES`
- `ORIGIN1`: `test_your_script_v1:filter_public_shas:1205`
- `PREVIOUS_APPROVAL_PATCH_APPLIED`: `NO`
- `RESTART`: `NO`
- `SOURCE_CHANGE`: `NO`
