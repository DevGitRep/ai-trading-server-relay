# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T11:14:12.515769+00:00`
- Run ID: `20260908T111410Z`
- Step: `READLIBRARYAPIROUTE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `LIBRARYAPIROUTEREAD`
- Next gate: `PATCHLIBRARYCARDS`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `DB_WRITE`: `NO`
- `FILE`: `indicator_lab_v1.py`
- `LINE1`: `return jsonify({`
- `LINE2`: `request.args.get(`
- `LINE3`: `return response`
- `LINE4`: `# PINE_LIBRARY_TIERED_UI_V1_BEGIN`
- `LINE5`: `_pl_support / &quot;pine_library_jurik_free_card_v1.json&quot;,`
- `LINE6`: `_pl_support / &quot;pine_library_jurik_pro_card_v1.json&quot;,`
- `LINE7`: `_pl_support / &quot;pine_library_jurik_internal_card_v1.json&quot;,`
- `LINE8`: `_pl_support / &quot;pine_library_jurik_free_report_v1.json&quot;,`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `OWNER`: `register_indicator_lab_routes`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
