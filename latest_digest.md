# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-10T14:40:20.294441+00:00`
- Run ID: `20260910T144017Z`
- Step: `READ_PIPELINE_INDICATOR_LOOKUP`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXACT_PIPELINE_INDICATOR_LOOKUP_EXPOSED`
- Next gate: `VERIFY_LOOKUP_KEY_AGAINST_RECENT_CANDIDATE`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CANONICAL_COMMAND`: `BENCHTEST_1_RECENT`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `FAILURE`: `PIPELINE_INDICATOR_MISSING`
- `INDICATOR_ASSIGNMENTS`: `1`
- `INDICATOR_SOURCE`: `con.execute(&#x27;n_SELECT_indicator_idn_FROM_pipeline_indicatorsn_WHERE_indicator_id=n_&#x27;,_(candidate_id,)).fetchone()`
- `OWNER`: `_v2_pipeline_insert_result_v1`
- `RESTART`: `NO`
- `SOURCE_CHANGE`: `NO`
- `SQL_LOOKUPS`: `4`
- `TYS_START_GATE`: `PASSED`
