# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T08:14:15.508908+00:00`
- Run ID: `20260911T081413Z`
- Step: `INSPECT_EXACT_LIBRARY_CARD_FLOW_ORDER`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXACT_LIBRARY_ROWS_FILTER_POINT_RESOLVED`
- Next gate: `ADD_APPROVED_SHA_FILTER_IMMEDIATELY_AFTER_LIBRARY_ROWS`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CALL1`: `1197:_bulk_candidate_maps`
- `CALL2`: `1201:_bulk_pipeline_metrics_v1`
- `CALL3`: `1213:_library_rows`
- `CALL4`: `1440:_candidate_ids_from_maps`
- `CALL_ORDER`: `_bulk_candidate_maps__bulk_pipeline_metrics_v1__library_rows__candidate_ids_from_maps`
- `CARD_ASSIGN_COUNT`: `1`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `FIRST_ROWS_USE_LINE`: `1229`
- `LIBRARY_ROWS_END_LINE`: `1213`
- `LIBRARY_ROWS_LINE`: `1213`
- `LIBRARY_ROWS_VAR`: `library_rows`
- `PREVIOUS_PATCH_APPLIED`: `NO`
- `RESTART`: `NO`
- `ROWS_USE1`: `1229:Assign:public_source_shas_=_set(__tys_filter_public_shas(_[_str(item[source_sha256])_for_item_in_library_rows_if_item[source_sha256]_]_)_)`
- `ROWS_USE2`: `1241:For:for_item_in_library_rows:_if_item[source_sha256]:_continue_missing_pairs.append(_(_item[script_id_part],_item[source_version],_)_)`
- `ROWS_USE3`: `1336:For:for_row_in_library_rows:_row_public_sha_=_(_row[source_sha256]_or_fallback_sha_by_pair.get(_(_row[script_id_part],_row[source_version],_),_,_)_or__)_if_row_public_sha:_if_row_public_sha_not_`
- `ROWS_USE_COUNT`: `3`
- `SOURCE_CHANGE`: `NO`
