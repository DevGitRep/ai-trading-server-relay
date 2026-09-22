# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-22T00:55:00.282860+00:00`
- Run ID: `20260922T005458Z`
- Step: `CASE4COLORFAMILY`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CASE4_COLOR_FAMILY_RULES_RECOVERED`
- Next gate: `PATCH_CASE4_CANONICAL_COLOR_CLASSIFICATION`

## Facts

- `CF00`: `def color_family(value):`
- `CF01`: `text   str(`
- `CF02`: `value`
- `CF03`: `).lower()`
- `CF04`: `EMPTY`
- `CF05`: `if (`
- `CF06`: `&quot;green&quot; in text`
- `CF07`: `or &quot;lime&quot; in text`
- `CF08`: `):`
- `CF09`: `return &quot;GREEN&quot;`
- `CF10`: `EMPTY`
- `CF11`: `if (`
- `CF12`: `&quot;red&quot; in text`
- `CF13`: `or &quot;maroon&quot; in text`
- `CF14`: `):`
- `CF15`: `return &quot;RED&quot;`
- `CF16`: `EMPTY`
- `CF17`: `m   re.search(`
- `CF18`: `r&quot;#([0-9a-f]{6})&quot;,`
- `DASHBOARD_RESTART`: `NO`
- `HEAD`: `939755327f6d`
- `PRODUCTION_CODE_WRITES`: `0`
- `PRODUCTION_DB_WRITES`: `0`
- `REPO_CLEAN`: `YES`
- `START_LINE`: `301`
