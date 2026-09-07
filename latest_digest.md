# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-07T14:58:25.676895+00:00`
- Run ID: `20260907T145823Z`
- Step: `TRACEAPICARDPRODUCER`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `APICARDPRODUCEREXACTLYTRACED`
- Next gate: `PATCHFIVEFIELDSATREALISTICPRODUCER`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `BLOCK1`: `_bench_rows = _bench_v31ae_con.execute( &quot;&quot;&quot; SELECT b.candidate_id, b.&quot;profit_factor&quot; AS _profit_factor, b.&quot;net_r`
- `BLOCK1LINE`: `1283`
- `BLOCK2`: `_bench_v31ae_con.execute( &quot;&quot;&quot; SELECT b.candidate_id, b.&quot;profit_factor&quot; AS _profit_factor, b.&quot;net_return_pct&quot; AS`
- `BLOCK2LINE`: `1283`
- `BLOCK3`: `_bench_metrics_by_name.setdefault( _name, [], ).append({ &quot;profit_factor&quot;: _row[&quot;_profit_factor&quot;], &quot;net_return_pc`
- `BLOCK3LINE`: `1321`
- `BLOCK4`: `_card[&quot;realistic_score&quot;] = None`
- `BLOCK4LINE`: `1344`
- `BLOCK5`: `_card[&quot;realistic_score&quot;] = float( _values[&quot;realistic_score&quot;] )`
- `BLOCK5LINE`: `1347`
- `BLOCK6`: `_metrics.update({ &quot;profit_factor&quot;: _values[&quot;profit_factor&quot;], &quot;net_return_pct&quot;: _values[&quot;net_return_pct&quot;], &quot;max_d`
- `BLOCK6LINE`: `1358`
- `BLOCK7`: `_card[&quot;metrics&quot;] = _metrics`
- `BLOCK7LINE`: `1366`
- `BLOCKN`: `7`
- `CARDSEXPR`: `load_library_cards( tier )`
- `CARDSLINE`: `1769`
- `CARDSVAR`: `cards`
- `CHANGES_MADE`: `NO`
- `COMPLETE`: `16`
- `DB_WRITE`: `NO`
- `JOIN_BY_ID`: `YES`
- `JS_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `NAME_MAPPING_USED`: `NO`
- `PAGECALL`: `_indicator_lab_library_page_v26( cards, tier, q=request.args.get( &quot;q&quot;, &quot;&quot;, ), sort_key=request.args.get( &quot;sort&quot;,`
- `PAGECALLLINE`: `1793`
- `PREFLIGHT_RERUN`: `NO`
- `PRODUCER`: `load_library_cards`
- `QUICK`: `ok`
- `REALWRITELINES`: `1344,1347`
- `REALWRITEN`: `2`
- `RESTART`: `NO`
- `SCORED`: `16`
- `SOURCE_CHANGE`: `NO`
