# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T11:04:19.110524+00:00`
- Run ID: `20260908T110417Z`
- Step: `READLIBSORTDISPATCH`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `LIBSORTDISPATCHREAD`
- Next gate: `PATCHLIBRARYCARDS`

## Facts

- `AST1`: `LIB:load_library_cards:906:cards.sort( key=_card_sort_key, reverse=True, )`
- `AST2`: `LIB:load_library_cards:907:_card_sort_key`
- `AST3`: `BACK:order_scalper_live_api:14369:live_trades.sort( key=lambda x: x[&quot;entry_epoch&quot;], reverse=True )`
- `AST4`: `BACK:order_scalper_db_api:14850:events.sort( key=lambda x: x.get(&quot;epoch&quot;, 0), reverse=True )`
- `AST5`: `BACK:get_historical_candles:591:out.sort(key=lambda x: x[&quot;timestamp&quot;])`
- `AST6`: `BACK:_restore_trade_state:2078:events.sort( key=lambda x: x.get(&quot;epoch&quot;, 0), reverse=True )`
- `AST7`: `BACK:order_scalper_exit_evaluation:10529:sorted( timeline.keys() )`
- `AST8`: `BACK:process_trade:645:sorted(values)`
- `BENCHTEST_RERUN`: `NO`
- `DB_WRITE`: `NO`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `REF1`: `LIB:525:def _card_sort_key(card):`
- `REF2`: `LIB:906:cards.sort(`
- `REF3`: `LIB:907:key=_card_sort_key,`
- `REF4`: `LIB:908:reverse=True,`
- `REF5`: `BACK:590:# sort ASC &amp; de-duplicate timestamps`
- `REF6`: `BACK:591:out.sort(key=lambda x: x[&quot;timestamp&quot;])`
- `REF7`: `BACK:645:ordered = sorted(values)`
- `REF8`: `BACK:2078:events.sort(`
- `REQ1`: `BACK:15067:return (0, &#x27;NO_BENCHTEST_SOURCE_SHA256&#x27;) | if &#x27;contract_version&#x27; in cols: | rows = con.execute(&#x27;\n SELEC`
- `REQ2`: `BACK:15070:semantics = &#x27;BENCHTEST_DUAL_12MONTH_V2_CURRENT_EXECUTABLE_SOURCES&#x27; | else: | rows = con.execute(&#x27;\n SELE`
- `REQ3`: `NONE`
- `REQ4`: `NONE`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
