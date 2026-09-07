# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-07T02:18:09.170503+00:00`
- Run ID: `20260907T021807Z`
- Step: `V31S_UNBOUNDLOCAL_CONTROLFLOW_READ`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CANDIDATE_IDS_CONTROL_FLOW_CAPTURED`
- Next gate: `ONE_MINIMAL_CONTROL_FLOW_SAFE_V31S_PATCH`

## Facts

- `APPEND`: `L1234:indent12:cards.append(card)`
- `APPEND_CONTROL`: `For@L1112:FOR:row in library_rows|Try@L963:TRY`
- `ASSIGN_1`: `L1215:indent16:candidate_ids = _candidate_ids_from_maps(sha, row[&#x27;chart_url&#x27;], candidate_sha_map, candidate_url_map)`
- `ASSIGN_1_CONTROL`: `If@L1186:IF:pro|For@L1112:FOR:row in library_rows|Try@L963:TRY`
- `BENCHTEST_RERUN`: `NO`
- `CANDIDATE_ASSIGN_COUNT`: `1`
- `CARDS_APPEND_COUNT`: `1`
- `CHANGES_MADE`: `NO`
- `DB_WRITE`: `NO`
- `MASTER_READ`: `YES`
- `PROVEN_SAME_CONTROL_PATH`: `NO`
- `RESTART`: `NO`
