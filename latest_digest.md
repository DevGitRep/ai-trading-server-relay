# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-07T10:41:38.813752+00:00`
- Run ID: `20260907T104136Z`
- Step: `READSCOREACTIVITY`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `ACTIVITYISBROADERTHANCLOSEDTRADES`
- Next gate: `VERIFYFROZENPRIMARYSCORETHENWIRESCOREPERSISTENCE`

## Facts

- `ACTKEYS`: `exposure_pct,trade_count`
- `ACTRET1`: `return bool( trades&gt;0 or ( exposure is not None and exposure&gt;0.0 ) )`
- `ACTRETURNS`: `1`
- `BENCHTEST_RERUN`: `NO`
- `CHANGES_MADE`: `NO`
- `CONFLIMITS`: `YES`
- `CONFRETURNS`: `1`
- `CURRENT`: `16`
- `DB_WRITE`: `NO`
- `EXPOSURE`: `99.98306697108067`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `QUICK`: `ok`
- `RESTART`: `NO`
- `RETURN`: `-58.61491326971059`
- `SCORE`: `8.487595661182382`
- `SOURCE_CHANGE`: `NO`
- `TARGETKEYN`: `2`
- `TARGETVALS`: `exposure_pct=None,trade_count=0`
- `TRADES`: `0`
- `USESEXPOSURE`: `YES`
- `USESMTM`: `NO`
- `USESOPEN`: `NO`
- `USESRETURN`: `YES`
- `USESTRADES`: `YES`
