# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-07T01:08:56.302905+00:00`
- Run ID: `20260907T010854Z`
- Step: `LIBRARY_BENCHTEST_BACKEND_FUNCTION_READ`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXACT_BACKEND_FUNCTION_STRUCTURE_CAPTURED`
- Next gate: `PATCH_ONLY_PROVEN_RESPONSE_MAPPING`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `CHANGES_MADE`: `NO`
- `FUNCTION`: `_indicator_library_ui_v2_benchtest`
- `FUNCTION_END`: `15115`
- `FUNCTION_LINE`: `15060`
- `MASTER_READ`: `YES`
- `RESPONSE_KEYS`: `NONE`
- `RESTART`: `NO`
- `SQL_1`: `benchtest_results_v1`
- `SQL_2`: `benchtest_results_v1`
- `SQL_3`: `SELECT DISTINCT source_sha256 FROM benchtest_results_v1 WHERE source_sha256 IS NOT NULL AND contract_version=?`
- `SQL_4`: `SELECT DISTINCT source_sha256 FROM benchtest_results_v1 WHERE source_sha256 IS NOT NULL`
- `SQL_COUNT`: `4`
