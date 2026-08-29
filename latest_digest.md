# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-08-29T20:14:10.761649+00:00`
- Run ID: `20260829T201408Z`
- Step: `EXPOSE_RESULT_KEY_CONTRACT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXACT_KEY_AND_LOOKUP_EXPRESSIONS_EXPOSED`
- Next gate: `PATCH_RESULT_KEY_MAPPING`

## Facts

- `CODE_CHANGED`: `NO`
- `DB_WRITE`: `NO`
- `DYNAMIC_KEYS`: `3`
- `KEY1`: `L4 const [dataPath, pinePath, configPath, outputPath] :`
- `KEY2`: `L30 indicator.input[key] : value;`
- `KEY3`: `L72 outputs[name] : rows.map(x :&gt; ({`
- `LOOKUP1`: `L2809 long_series : find_series(result, signals[&#x27;long&#x27;])`
- `LOOKUP2`: `L2814 short_series : find_series(result, signals[&#x27;short&#x27;])`
- `LOOKUP3`: `L2848 metrics, trades : evaluate(candles, long_series, short_series)`
- `LOOKUP4`: `L2885 thumbnail : build_thumbnail(candidate_id, thumb_run, candles, signals, long_series, short_series, result, plo`
- `LOOKUPS`: `4`
- `TESTING`: `NO`
