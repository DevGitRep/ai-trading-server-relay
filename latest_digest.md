# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-17T08:33:20.685274+00:00`
- Run ID: `20260917T083318Z`
- Step: `PINER_SELECTION_LOGIC`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `PINER_EXACT_SELECTION_ASSIGNMENT_RESOLVED`
- Next gate: `RUN_REAL_YEAR_WITH_ACTUAL_SELECTED_RAW_CONTRACT`

## Facts

- `ATB_CHANGED`: `NO`
- `CONTRACT_APPENDS`: `L132:contracts.append(contract)`
- `CONTRACT_GUARDS`: `NONE`
- `DASHBOARD_RESTART`: `NO`
- `DB_WRITES`: `0`
- `FAILURE`: `NONE`
- `FLOW`: `L94:IF:not_PINER_CONTRACT.exists(),L115:IF:obj.get(ok)_is_not_True,L118:ASSIGN:contracts,L120:FOR:contract-o`
- `INTERNAL_RC`: `0`
- `READ_ONLY`: `YES`
- `RETURN_SELECTED_FIELDS`: `NONE`
- `SELECTED_ASSIGNMENTS`: `L137:sorted(contracts,_key=_sort_key)[0]`
- `SORT_ASSIGNMENTS`: `NONE`
