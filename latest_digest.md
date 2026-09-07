# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-07T01:35:20.516816+00:00`
- Run ID: `20260907T013518Z`
- Step: `LIBRARY_CARD_SOURCE_CALLER_TRACE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `LIBRARY_CARD_SOURCE_CALLER_CAPTURED`
- Next gate: `PATCH_REALISTIC_SCORE_AT_PROVEN_CARD_SOURCE`

## Facts

- `ASSIGN_1`: `indicator_lab_library_page_api_v26:L1759:cards = load_library_cards(tier)`
- `ASSIGN_2`: `indicator_lab_home:L1826:_ui_cards_all = _pine_library_cards(_ui_effective_tier)`
- `BENCHTEST_RERUN`: `NO`
- `CALL_1`: `indicator_lab_library_page_api_v26:L1783:arg=cards`
- `CALL_2`: `indicator_lab_home:L1827:arg=_ui_cards_all`
- `CALL_COUNT`: `2`
- `CHANGES_MADE`: `NO`
- `MASTER_READ`: `YES`
- `RESTART`: `NO`
