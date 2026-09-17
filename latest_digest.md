# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-17T11:40:35.074015+00:00`
- Run ID: `20260917T114033Z`
- Step: `INSPECT_EXACT_PINER_EXTREMA_RULE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `PINER_EXTREMA_EXACT_RULE_INSPECTED`
- Next gate: `IMPLEMENT_PARSER_AGAINST_EXACT_PINER_EXTREMA_RULE`

## Facts

- `ATB_CHANGED`: `NO`
- `DASHBOARD_RESTART`: `NO`
- `DB_WRITES`: `0`
- `FAILURE`: `NONE`
- `HAS_LONG`: `NO`
- `HAS_MAXIMA`: `YES`
- `HAS_MINIMA`: `YES`
- `HAS_SHORT`: `NO`
- `INTERNAL_RC`: `0`
- `READ_ONLY`: `YES`
- `RELEVANT_LINES`: `12`
- `RULE_1`: `2:const_minima=[]`
- `RULE_10`: `16:if(b&gt;a_&amp;&amp;_b&gt;c)`
- `RULE_11`: `17:maxima.push(candleEvent(candles,i))`
- `RULE_12`: `21:return_minima,maxima`
- `RULE_2`: `3:const_maxima=[]`
- `RULE_3`: `5:for(let_i=1i&lt;series.length-1i++)`
- `RULE_4`: `6:const_a=series[i-1]`
- `RULE_5`: `7:const_b=series[i]`
- `RULE_6`: `8:const_c=series[i+1]`
- `RULE_7`: `10:if(![a,b,c].every(Number.isFinite))_continue`
- `RULE_8`: `12:if(b&lt;a_&amp;&amp;_b&lt;c)`
- `RULE_9`: `13:minima.push(candleEvent(candles,i))`
- `THREE_POINT_LOOP`: `YES`
