# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-22T09:48:20.570289+00:00`
- Run ID: `20260922T094818Z`
- Step: `CASE4PREFLIGHTTRACE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CASE4_TESTPINE_PREFLIGHT_TRACED`
- Next gate: `DECIDE_CASE4_FINAL_NUMERIC_STOP_OR_INSPECT_PREFLIGHT_RUNTIME`

## Facts

- `DASHBOARD_RESTART`: `NO`
- `F1`: `TESTPINE RUNNER BLOCK`
- `F10`: `print(&quot;ERROR &quot; + str(message), file sys.stderr)`
- `F11`: `raise SystemExit(1)`
- `F12`: `NONE`
- `F13`: `NONE`
- `F14`: `def get_runner():`
- `F15`: `for path in RUNNERS:`
- `F16`: `if path.is_file():`
- `F17`: `return path`
- `F18`: `NONE`
- `F19`: `fail(&quot;testpine-preflight not found&quot;)`
- `F2`: `DASH / &quot;tools/testpine-preflight&quot;,`
- `F20`: `NONE`
- `F21`: `NONE`
- `F22`: `def already_tested(conn, sha):`
- `F23`: `row   conn.execute(`
- `F24`: `&quot;&quot;&quot;`
- `F25`: `SELECT 1`
- `F26`: `FROM candidates`
- `F27`: `WHERE source_sha256 ?`
- `F28`: `AND (`
- `F29`: `COALESCE(notes,&#x27;&#x27;)`
- `F3`: `DASH / &quot;testpine-preflight&quot;,`
- `F30`: `LIKE &#x27;%TESTPINE_BASELINE_V1_ATTEMPTED %&#x27;`
- `F4`: `]`
- `F5`: `NONE`
- `F6`: `ATTEMPT   &quot;TESTPINE_BASELINE_V1_ATTEMPTED &quot;`
- `F7`: `NONE`
- `F8`: `NONE`
- `F9`: `def fail(message):`
- `HEAD`: `939755327f6d`
- `LINE_COUNT`: `227`
- `PRODUCTION_CODE_WRITES`: `0`
- `PRODUCTION_DB_WRITES`: `0`
- `REPO_CLEAN`: `YES`
