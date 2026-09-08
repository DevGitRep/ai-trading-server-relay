# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T11:15:04.548849+00:00`
- Run ID: `20260908T111502Z`
- Step: `READLIBRARYROUTESORT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `LIBRARYROUTESORTREAD`
- Next gate: `PATCHLIBRARYCARDS`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `CTX1`: `765:) | def indicator_lab_tiered_research_api_v1(): | from flask import jsonify | tier=_indicator_lab_requested_tie`
- `CTX2`: `774:) | return jsonify({ | &quot;ok&quot;:True, | &quot;tier&quot;:tier,`
- `CTX3`: `784:from flask import ( | abort, | jsonify, | redirect, | render_template,`
- `CTX4`: `807:raw_token = str( | request.args.get( | &quot;token&quot;, | &quot;&quot;,`
- `DB_WRITE`: `NO`
- `LINE1`: `765:from flask import jsonify`
- `LINE2`: `774:return jsonify({`
- `LINE3`: `784:jsonify,`
- `LINE4`: `807:request.args.get(`
- `LINE5`: `849:return response`
- `LINE6`: `904:return False`
- `LINE7`: `915:return True`
- `LINE8`: `922:return True`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `OWNER`: `register_indicator_lab_routes`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
