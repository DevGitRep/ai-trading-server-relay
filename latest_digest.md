# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-07T01:25:26.456980+00:00`
- Run ID: `20260907T012524Z`
- Step: `LIBRARY_SCORE_FETCH_URL_AND_PAYLOAD_READ`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `FETCH_URL_AND_PAYLOAD_FLOW_CAPTURED`
- Next gate: `MINIMAL_REALISTIC_SCORE_RESPONSE_MAPPING_PATCH`

## Facts

- `A_1`: `L864:const response=await fetch(`
- `A_2`: `L865:url.toString(),`
- `A_3`: `L880:const payload=await response.json();`
- `BENCHTEST_RERUN`: `NO`
- `B_1`: `L968:fetch(`
- `B_2`: `L969:`/indicator-lab/api/library-stats?view_as=${encodeURIComponent(tier)}``
- `B_3`: `L978:return r.json();`
- `CHANGES_MADE`: `NO`
- `MASTER_READ`: `YES`
- `RESTART`: `NO`
