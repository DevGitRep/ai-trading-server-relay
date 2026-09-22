# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-22T00:56:34.184614+00:00`
- Run ID: `20260922T005632Z`
- Step: `CASE4RGBDECISION`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CASE4_RGB_DECISION_RULES_RECOVERED`
- Next gate: `PATCH_CASE4_CANONICAL_COLOR_CLASSIFICATION`

## Facts

- `DASHBOARD_RESTART`: `NO`
- `HEAD`: `939755327f6d`
- `L337`: ``
- `L338`: `b   int(`
- `L339`: `value[4:6],`
- `L340`: `16,`
- `L341`: `)`
- `L342`: ``
- `L343`: `if (`
- `L344`: `g &gt; r * 1.2`
- `L345`: `and g &gt; b * 1.2`
- `L346`: `):`
- `L347`: `return &quot;GREEN&quot;`
- `L348`: ``
- `L349`: `if (`
- `L350`: `r &gt; g * 1.2`
- `L351`: `and r &gt; b * 1.2`
- `L352`: `):`
- `PRODUCTION_CODE_WRITES`: `0`
- `PRODUCTION_DB_WRITES`: `0`
- `REPO_CLEAN`: `YES`
