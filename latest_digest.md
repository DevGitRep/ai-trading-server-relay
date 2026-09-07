# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-07T14:35:51.373044+00:00`
- Run ID: `20260907T143549Z`
- Step: `READCARDPROJECTION`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CARDPROJECTIONSEAMEXACTLYCAPTURED`
- Next gate: `PATCHFIVEPRIMARYFIELDSONPROVENSEAM`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `CHANGES_MADE`: `NO`
- `COMPLETE`: `16`
- `DB_WRITE`: `NO`
- `JOIN_BY_ID`: `YES`
- `JS_CHANGE`: `NO`
- `LIB1`: `card = { &quot;script_id_part&quot;: row[&quot;script_id_part&quot;], &quot;name&quot;: row[&quot;name&quot;] or &quot;Untitled indicator&quot;, &quot;author&quot;: row[&quot;author&quot;] o`
- `LIB1LINE`: `1156`
- `LIB2`: `_best_metrics_from_map( candidate_ids, bench_metrics_map, )`
- `LIB2LINE`: `1241`
- `LIB3`: `metrics = _best_metrics_from_map( candidate_ids, bench_metrics_map, )`
- `LIB3LINE`: `1241`
- `LIB4`: `card[&quot;metrics&quot;] = ( metrics or _empty_metrics() )`
- `LIB4LINE`: `1246`
- `LIBSEAMN`: `12`
- `MARKERN`: `3`
- `MASTER_READ`: `YES`
- `NAME_MAPPING_USED`: `NO`
- `PAGE1`: `rows = [ card for card in cards if ( not q_norm or q_norm in _norm_title(card) ) ]`
- `PAGE1LINE`: `613`
- `PAGE2`: `metric_fields = { &quot;realistic&quot;: &quot;realistic_score&quot;, &quot;profit&quot;: &quot;profit_factor&quot;, &quot;return&quot;: &quot;net_return_pct&quot;, &quot;win&quot;: &quot;win_rat`
- `PAGE2LINE`: `623`
- `PAGE3`: `{ &quot;realistic&quot;: &quot;realistic_score&quot;, &quot;profit&quot;: &quot;profit_factor&quot;, &quot;return&quot;: &quot;net_return_pct&quot;, &quot;win&quot;: &quot;win_rate_pct&quot;, }`
- `PAGE3LINE`: `623`
- `PAGE4`: `card.get(&quot;realistic_score&quot;)`
- `PAGE4LINE`: `651`
- `PAGESEAMN`: `11`
- `PREFLIGHT_RERUN`: `NO`
- `QUICK`: `ok`
- `REALWRITEN`: `13`
- `RESTART`: `NO`
- `SCORED`: `16`
- `SOURCE_CHANGE`: `NO`
- `WRITE1`: `LIB:1283:_bench_rows = _bench_v31ae_con.execute( &quot;&quot;&quot; SELECT b.candidate_id, b.&quot;profit_factor&quot; AS _profit_factor, b.&quot;net_`
- `WRITE2`: `LIB:1283:_bench_v31ae_con.execute( &quot;&quot;&quot; SELECT b.candidate_id, b.&quot;profit_factor&quot; AS _profit_factor, b.&quot;net_return_pct&quot; AS`
- `WRITE3`: `LIB:1321:_bench_metrics_by_name.setdefault( _name, [], ).append({ &quot;profit_factor&quot;: _row[&quot;_profit_factor&quot;], &quot;net_return_p`
- `WRITE4`: `LIB:1324:{ &quot;profit_factor&quot;: _row[&quot;_profit_factor&quot;], &quot;net_return_pct&quot;: _row[&quot;_net_return_pct&quot;], &quot;max_drawdown_pct&quot;: _row[`
