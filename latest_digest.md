# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-17T08:00:28.701638+00:00`
- Run ID: `20260917T080026Z`
- Step: `RESOLVE_PINER_NONSELECTING_HYPOTHESIS_EXECUTION_ROUTE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `PINER_EXECUTION_ROUTE_DISCOVERY_BLOCKED`
- Next gate: `FIX_ONLY_REPORTED_PINER_ROUTE_FAILURE`

## Facts

- `ALL_CANDIDATES_ROUTE`: `NO`
- `ATB_CHANGED`: `NO`
- `CANDIDATE_FUNCTIONS`: `select_piner_candidate(source,candles)`
- `CANDLE_FUNCTIONS`: `_candles(candles),select_piner_candidate(source,candles)`
- `DASHBOARD_RESTART`: `NO`
- `DB_WRITES`: `0`
- `EVENT_FUNCTIONS`: `_sort_key(contract),select_piner_candidate(source,candles)`
- `EXECUTION_ROUTE`: `NONE`
- `FAILURE`: `SELECT_PINER_CANDIDATE_NOT_FOUND`
- `INTERNAL_RC`: `20`
- `PINER_FUNCTIONS`: `_scalar,_candles,_sort_key,select_piner_candidate`
- `PINER_SIGNATURES`: `_scalar(value),_candles(candles),_sort_key(contract),select_piner_candidate(source,candles)`
- `READ_ONLY`: `YES`
- `RETURN_KEYS`: `select_piner_candidate=author_label|events|evidence|expressions|lane|priority|provider|reason|validation`
- `SELECTOR_CALLS`: `NONE`
- `SELECTOR_SIGNATURE`: `NONE`
- `SUBPROCESS_FUNCTIONS`: `select_piner_candidate(source,candles)`
- `YEAR_RESELECTION`: `NO`
