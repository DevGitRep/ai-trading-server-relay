# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-12T11:34:53.580914+00:00`
- Run ID: `20260912T113451Z`
- Step: `FREEPROFILETRACE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `TRACE_CAPTURED`
- Next gate: `LOCATE_FREE_DATA_LOSS`

## Facts

- `TRACE01`: `L2388:requested_tier = str(`
- `TRACE02`: `L2389:_indicator_lab_requested_tier()`
- `TRACE03`: `L2390:or &#x27;FREE&#x27;`
- `TRACE04`: `L2395:and requested_tier`
- `TRACE05`: `L2397:&#x27;FREE&#x27;,`
- `TRACE06`: `L2402:effective_tier = requested_tier`
- `TRACE07`: `L2404:effective_tier = &#x27;FREE&#x27;`
- `TRACE08`: `L2406:benchtest_metrics = (`
- `TRACE09`: `L2409:effective_tier,`
- `TRACE10`: `L2413:# FREE_DESCRIPTIVE_PROFILE_V1`
- `TRACE11`: `L2414:if effective_tier == &#x27;FREE&#x27;:`
- `TRACE12`: `L2422:benchtest_metrics = dict(`
