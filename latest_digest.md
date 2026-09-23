# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-23T18:23:09.481036+00:00`
- Run ID: `20260923T182307Z`
- Step: `CAPTUREEXACTFRONTENDSTRUCTURE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXACT_FRONTEND_STRUCTURE_CAPTURED`
- Next gate: `PATCH_FRONTEND_15DAY_NAVIGATION`

## Facts

- `DASHBOARD_RESTART`: `NO`
- `DECL_COUNT`: `16`
- `FILE_DELETES`: `0`
- `FUNC_HEADER`: `const start=async()=&gt;{`
- `GIT_COMMITS`: `0`
- `GIT_PUSHES`: `0`
- `HEAD`: `28209506cc98`
- `HTML_LINE_COUNT`: `9`
- `L1181`: `)}/bench-chart-data?view_as=${encodeURIComponent(`
- `L1186`: `const response=await fetch(`
- `L1197`: ``chart ${response.status}``
- `L1203`: `const candles=Array.isArray(`
- `L1204`: `payload.candles`
- `L1206`: `?payload.candles`
- `L1277`: `payload.mode!==&quot;candles&quot;`
- `L1278`: `||candles.length&lt;2`
- `L1281`: `&#x27;&lt;div class=&quot;irl-bench-chart-empty&quot;&gt;&#x27;`
- `L1285`: `host.dataset.chartState=&quot;empty&quot;;`
- `L1289`: `host.dataset.chartState=&quot;ready&quot;;`
- `L1297`: `?`${payload.display_timeframe} display candles``
- `PRODUCTION_CODE_WRITES`: `0`
- `PRODUCTION_DB_WRITES`: `0`
- `REPO_CLEAN`: `YES`
