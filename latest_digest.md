# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-12T15:12:06.822930+00:00`
- Run ID: `20260912T151204Z`
- Step: `RESOLVESCRIPTIDEXPRESSION`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `REPORT_ROUTE_IDENTIFIER_CONTEXT_CAPTURED`
- Next gate: `APPLY_MINIMAL_CONFIRMED_IDENTIFIER_FIX`

## Facts

- `ROUTE01`: `L2343:SELECT *`
- `ROUTE02`: `L2344:FROM scripts`
- `ROUTE03`: `L2345:WHERE script_id_part=?`
- `ROUTE04`: `L2347:(candidate_id,),`
- `ROUTE05`: `L2348:).fetchone()`
- `ROUTE06`: `L2354:record = dict(script)`
- `ROUTE07`: `L2358:SELECT`
- `ROUTE08`: `L2359:script_id_part,`
- `ROUTE09`: `L2367:WHERE script_id_part=?`
- `ROUTE10`: `L2371:(candidate_id,),`
- `ROUTE11`: `L2372:).fetchone()`
- `ROUTE12`: `L2407:_pine_report_metrics(`
- `ROUTE13`: `L2408:candidate_id,`
- `ROUTE14`: `L2416:_pine_report_metrics(`
- `ROUTE15`: `L2417:candidate_id,`
