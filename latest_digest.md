# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-21T21:22:10.491364+00:00`
- Run ID: `20260921T212208Z`
- Step: `CASE2OPTIMIZED`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CASE2_OPTIMIZED_FORMULAS_RECOVERED`
- Next gate: `IMPLEMENT_CASE2_INDEPENDENT_LEAN_SIGNAL_PORT_AND_COMPARE_525600_BARS`

## Facts

- `CORE_READY`: `YES`
- `DASHBOARD_RESTART`: `NO`
- `EXTRA_USE`: `58:extraLength  EQ  input.int(50, minval EQ 1, title EQ &quot;Extra Smoothing Length&quot;) ; 64:optimizedSMA1  EQ  (ta.ema(source, length1) + ta.ema(source, length2) + ta.ema(source, extraLength)) / 3`
- `HEAD`: `939755327f6d`
- `OPT1`: `(ta.ema(source, length1) + ta.ema(source, length2) + ta.ema(source, extraLength)) / 3`
- `OPT2`: `(ta.ema(source, math.round(length1 * 1.5)) + ta.ema(source, math.round(length2 * 1.5)) + ta.ema(source, math.round(extraLength * 1.5))) / 3`
- `PRODUCTION_CODE_WRITES`: `0`
- `PRODUCTION_DB_WRITES`: `0`
- `REPO_CLEAN`: `YES`
