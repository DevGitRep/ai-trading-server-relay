# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-07T01:26:00.909177+00:00`
- Run ID: `20260907T012558Z`
- Step: `LIBRARY_FETCH_A_FULL_FLOW_READ`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `FETCH_A_URL_AND_CARD_FLOW_CAPTURED`
- Next gate: `PATCH_ONLY_PROVEN_REALISTIC_SCORE_SEAM`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `CHANGES_MADE`: `NO`
- `FLOW_1`: `L838:url.searchParams.set(`
- `FLOW_2`: `L845:url.searchParams.set(`
- `FLOW_3`: `L850:url.searchParams.set(`
- `FLOW_4`: `L864:const response=await fetch(`
- `FLOW_5`: `L865:url.toString(),`
- `FLOW_6`: `L880:const payload=await response.json();`
- `FLOW_7`: `L887:payload`
- `MASTER_READ`: `YES`
- `RANGE`: `L835-920`
- `RESTART`: `NO`
