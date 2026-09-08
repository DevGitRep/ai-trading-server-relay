# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T11:21:43.394670+00:00`
- Run ID: `20260908T112141Z`
- Step: `READPAGESORTLOGIC`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `PAGESORTLOGICREAD`
- Next gate: `PATCHLIBRARYCARDS`

## Facts

- `AST1`: `623:metric_fields = { &quot;realistic&quot;: &quot;realistic_score&quot;, &quot;profit&quot;: &quot;profit_factor&quot;, &quot;return&quot;: &quot;net_return_pct&quot;, &quot;`
- `AST2`: `634:sort_key = ( sort_key if sort_key in metric_fields else &quot;realistic&quot; )`
- `AST3`: `641:field = metric_fields[ sort_key ]`
- `AST4`: `740:return { &quot;items&quot;: items, &quot;total&quot;: total, &quot;page&quot;: page, &quot;pages&quot;: pages, &quot;page_size&quot;: page_size, &quot;sort&quot;: sor`
- `AST5`: `649:if field == &quot;realistic_score&quot;: try: value = card.get(&quot;realistic_score&quot;) if value is None: return float(&quot;-i`
- `AST6`: `651:value = card.get(&quot;realistic_score&quot;)`
- `AST7`: `651:card.get(&quot;realistic_score&quot;)`
- `AST8`: `NONE`
- `BENCHTEST_RERUN`: `NO`
- `CONST1`: `realistic`
- `CONST2`: `profit`
- `CONST3`: `return`
- `CONST4`: `win`
- `CONST5`: `realistic_score`
- `CONST6`: `profit_factor`
- `DB_WRITE`: `NO`
- `LINE1`: `586:sort_key=&quot;realistic&quot;,`
- `LINE2`: `624:&quot;realistic&quot;:`
- `LINE3`: `625:&quot;realistic_score&quot;,`
- `LINE4`: `627:&quot;profit_factor&quot;,`
- `LINE5`: `629:&quot;net_return_pct&quot;,`
- `LINE6`: `631:&quot;win_rate_pct&quot;,`
- `LINE7`: `634:sort_key = (`
- `LINE8`: `635:sort_key`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
