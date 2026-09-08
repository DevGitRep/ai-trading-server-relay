# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T10:00:15.328109+00:00`
- Run ID: `20260908T100013Z`
- Step: `READBUSELLARTIFACTS`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `BUSELLARTIFACTSREAD`
- Next gate: `PATCHBUSELLSIGNALS`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `DB_WRITE`: `NO`
- `JS1`: `/* PAGER_WRAP_AWARE_AND_BUY_SELL_MARKERS_V29O */`
- `JS2`: `const buyMarkerCount=`
- `JS3`: `markerAction(marker)===&quot;BUY&quot;`
- `LARGE1`: `NONE`
- `LARGE2`: `NONE`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `OLD1`: `if source_sha256: resin=con.execute( &quot;&quot;&quot; SELECT plots_json, captured_at FROM resin_native_outputs WHERE source_sha256=? AND error_stage IS N`
- `OLD2`: `resin=con.execute( &quot;&quot;&quot; SELECT plots_json, captured_at FROM resin_native_outputs WHERE source_sha256=? AND error_stage IS NULL ORDER BY captu`
- `OLD3`: `try: plots=_chart_json.loads( resin[&quot;plots_json&quot;] or &quot;[]&quot; ) except Exception: plots=[]`
- `PLOTMATCH`: `1`
- `PLOTSHAPE`: `L:6`
- `PREFLIGHT_RERUN`: `NO`
- `QUICK`: `ok`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SERIES1`: `NONE`
- `SERIES2`: `NONE`
- `SERIES3`: `NONE`
- `SOURCE_CHANGE`: `NO`
