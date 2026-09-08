# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T11:17:48.744438+00:00`
- Run ID: `20260908T111746Z`
- Step: `READLIBRARYHANDLERREST`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `LIBRARYHANDLERRESTREAD`
- Next gate: `PATCHLIBRARYCARDS`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `BODY10`: `payload = _indicator_lab_library_page_v26( | cards, | tier,`
- `BODY11`: `q=request.args.get( | &quot;q&quot;, | &quot;&quot;,`
- `BODY12`: `), | sort_key=request.args.get( | &quot;sort&quot;,`
- `BODY13`: `&quot;realistic&quot;, | ), | page=page,`
- `BODY14`: `page_size=page_size, | ) | payload[&quot;ok&quot;] = True`
- `BODY15`: `payload[&quot;tier&quot;] = tier | response = jsonify( | payload`
- `BODY16`: `) | response.headers[ | &quot;Cache-Control&quot;`
- `BODY7`: `try: | page_size = int( | request.args.get(`
- `BODY8`: `&quot;page_size&quot;, | &quot;12&quot;, | )`
- `BODY9`: `) | except Exception: | page_size = 12`
- `DB_WRITE`: `NO`
- `HANDLER`: `indicator_lab_library_page_api_v26`
- `LINES`: `50`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `REL1`: `request.args.get(`
- `REL10`: `return response`
- `REL2`: `page_size = int(`
- `REL3`: `&quot;page_size&quot;,`
- `REL4`: `page_size = 12`
- `REL5`: `q=request.args.get(`
- `REL6`: `sort_key=request.args.get(`
- `REL7`: `&quot;sort&quot;,`
- `REL8`: `&quot;realistic&quot;,`
- `REL9`: `page_size=page_size,`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
