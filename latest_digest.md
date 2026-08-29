# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-08-29T07:35:52.822014+00:00`
- Run ID: `20260829T073516Z`
- Step: `JURIK_LITERAL_EXISTING_CANDLE_ROUTE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `LITERAL_JURIK_ROUTE_EXPOSED_EXACT_EXISTING_CANDLE_GATE`
- Next gate: `FIX_ONLY_THE_REPORTED_RESOLVE_EXISTING_DATASET_OR_LOAD_CANDLES_ERROR`

## Facts

- `CANDLE_LOADER`: `load_candles`
- `CANDLE_ROWS`: `2`
- `DATASET_RESOLVER`: `resolve_existing_dataset`
- `DISCOVERY_USED`: `NO`
- `EXECUTOR`: `parameter_runner.py`
- `NEW_CANDLE_LOADER`: `NO`
- `NEW_EVALUATOR`: `NO`
- `PIPELINE_CODE_CHANGED`: `NO`
- `REFERENCE`: `JURIK_TREND_RIBBON_QUANTALGO`
- `REPLAY_RC`: `1`
- `RUNTIME_ERROR`: `TypeError: Object of type PosixPath is not JSON serializable`
