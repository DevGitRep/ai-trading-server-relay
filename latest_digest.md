# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T08:30:18.339772+00:00`
- Run ID: `20260908T083016Z`
- Step: `READCHARTRUTEWIRE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CHARTROUTEWIREREAD`
- Next gate: `PATCHREPORTV2FINAL`

## Facts

- `ATTRS`: `NONE`
- `BENCHTEST_RERUN`: `NO`
- `CURRENT_PATHS`: `/indicator-lab/strategy/&lt;candidate_id&gt;`
- `CURRENT_ROUTE`: `NO`
- `DATASET`: `chartState,pagerVisualMode`
- `DB_WRITE`: `NO`
- `DECORATOR`: `app.route( &quot;/indicator-lab/strategy/&lt;candidate_id&gt;/bench-chart-data&quot;, methods=[&quot;GET&quot;], )`
- `JS_CALLS`: `fetch,irlReportNativeChartV28C,json,loadPage,requestAnimationFrame`
- `JS_URL1`: `const response=await fetch(`
- `JS_URL2`: `const payload=await response.json();`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `RESPONSE`: `ok,mode,pair,source_timeframe,display_timeframe,source_candle_count,display_candle_count,candles,markers,dataset_start,dataset_end`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
- `TRADE1`: `if run_id: trade_rows=con.execute( &quot;&quot;&quot; SELECT trade_no, candidate_id, raw_json FROM benchtest_trades_v1 WHERE run_id=? ORDER BY CAST(trade_no AS`
- `TRADE2`: `trade_rows=con.execute( &quot;&quot;&quot; SELECT trade_no, candidate_id, raw_json FROM benchtest_trades_v1 WHERE run_id=? ORDER BY CAST(trade_no AS INTEGER) LI`
