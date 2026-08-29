# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-08-29T19:30:15.563635+00:00`
- Run ID: `20260829T193013Z`
- Step: `IDENTIFY_TESTPINE_BLOCKING_EARLY_RETURN`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `BLOCKING_RETURN_CONDITIONS_EXTRACTED`
- Next gate: `FIX_ONLY_IF_LIBRARY_MODE_EARLY_EXIT_IS_WRONG`

## Facts

- `CODE_CHANGED`: `NO`
- `DB_WRITE`: `NO`
- `R1_GUARD`: `NONE`
- `R1_LINE`: `2807`
- `R1_REASON`: `trades`
- `R1_VARS`: ``
- `R2_GUARD`: `long_series is None or short_series is None`
- `R2_LINE`: `2844`
- `R2_REASON`: `trades`
- `R2_VARS`: `long_series,short_series`
- `R3_GUARD`: `NONE`
- `R3_LINE`: `2877`
- `R3_REASON`: `trades`
- `R3_VARS`: ``
- `RETURNS`: `3`
- `TESTING`: `NO`
