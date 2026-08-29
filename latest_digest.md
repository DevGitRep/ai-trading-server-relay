# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-08-29T19:37:27.750003+00:00`
- Run ID: `20260829T193725Z`
- Step: `TRACE_SIGNAL_NAME_TO_RUNNER_RESULT_CONTRACT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `SIGNAL_NAME_AND_RESULT_LOOKUP_CONTRACT_CAPTURED`
- Next gate: `FIX_EXPLICIT_SIGNAL_MAPPING_ONLY_IF_CONTRACT_MISMATCHED`

## Facts

- `CODE_CHANGED`: `NO`
- `DB_WRITE`: `NO`
- `LONG_EXPR`: `metrics, trades : evaluate(candles, long_series, short_series)`
- `PATTERNS`: `pattern;\b[A-Za-z_][A-Za-z0-9_]*\b`
- `RESULT_ACCESS`: `NONE`
- `RETURNS`: `{&#x27;long&#x27;: long_var, &#x27;short&#x27;: short_var};None;None`
- `SHORT_EXPR`: `metrics, trades : evaluate(candles, long_series, short_series)`
- `SIGNAL_LINE`: `2714`
- `TESTING`: `NO`
- `TOKENS`: `LONG,SHORT,alertcondition\s*\(\s*([A-Za-z_][A-,buy_signal,buysignal,long,long_signal,longsignal,plotshape\s*\(\s*([A-Za-z_][A-Za-z0,sell_sig`
