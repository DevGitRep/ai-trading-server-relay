# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-17T06:48:39.910569+00:00`
- Run ID: `20260917T064837Z`
- Step: `RESOLVE_REAL_FULL_YEAR_RUNTIME_AND_DATA_SEAMS`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `REAL_FULL_YEAR_EXECUTION_SEAM_RESOLUTION_BLOCKED`
- Next gate: `FIX_ONLY_REPORTED_EXECUTION_SEAM_RESOLUTION_FAILURE`

## Facts

- `ARCHITECTURE_REDISCOVERY`: `NO`
- `ATB_CHANGED`: `NO`
- `DASHBOARD_RESTART`: `NO`
- `DB_WRITES`: `0`
- `EVENT_CALLS`: `_piner_selected.get(events,_),len(_piner_events.get(LONG,_[])),len(_piner_events.get(SHORT,_[])),outcome.update(status`
- `EXECUTION_SEAM`: `NONE`
- `FAILURE`: `[Errno_2]_No_such_file_or_directory:_rg`
- `INTERNAL_RC`: `20`
- `PINER_SIGNATURES`: `select_piner_candidate(source,candles)`
- `READY_TO_EXECUTE`: `NO`
- `RUNNER_CALLS`: `runner(source,_candles),check(source,_candles,_item,_runner=runner)`
- `RUNTIME_SIGNATURES`: `runtime_candidates(result,candles),validate_runtime(source,candles,candidate,runner)`
- `SELECTED_CALLS`: `_piner_selected.get(events,_)`
- `SELECT_ARGS`: `source,candles`
- `SELECT_ASSIGNMENT`: `_piner_selected_=__select_piner_candidate(source,_candles)`
- `SELECT_CALL`: `_select_piner_candidate`
- `YEAR_DATA_REFS`: `NONE`
- `YEAR_DATA_SEAM`: `NONE`
- `YEAR_LOADER_REFS`: `NONE`
