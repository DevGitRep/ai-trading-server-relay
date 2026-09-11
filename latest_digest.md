# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T11:13:58.659139+00:00`
- Run ID: `20260911T111356Z`
- Step: `INSPECT_EXACT_RESULT_DICT_BEFORE_INSERT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `RESULT_DICT_ALREADY_HAS_METRIC_KEYS`
- Next gate: `TRACE_ONLY_EXISTING_METRIC_EXPRESSIONS`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `METRIC1`: `trade_count:primary.get(&#x27;trade_count&#x27;)`
- `METRIC2`: `net_return_pct:primary.get(&#x27;net_return_pct&#x27;)`
- `METRIC3`: `max_drawdown_pct:primary.get(&#x27;max_drawdown_pct&#x27;)`
- `METRIC4`: `profit_factor:primary.get(&#x27;profit_factor&#x27;)`
- `METRIC5`: `win_rate_pct:primary.get(&#x27;win_rate_pct&#x27;)`
- `METRIC6`: `secondary_net_return_pct:secondary.get(&#x27;net_return_pct&#x27;)`
- `METRIC7`: `secondary_max_drawdown_pct:secondary.get(&#x27;max_drawdown_pct&#x27;)`
- `METRIC8`: `secondary_profit_factor:secondary.get(&#x27;profit_factor&#x27;)`
- `METRIC9`: `secondary_win_rate_pct:secondary.get(&#x27;win_rate_pct&#x27;)`
- `METRIC_KEYS_MISSING`: `NONE`
- `METRIC_KEYS_PRESENT`: `trade_count,net_return_pct,max_drawdown_pct,profit_factor,win_rate_pct,secondary_net_return_pct,secondary_max_drawdown_pct,secondary_profit_factor,secondary_win_rate_pct`
- `RESTART`: `NO`
- `RESULT_DICT_LINE`: `4605`
- `RESULT_KEY_COUNT`: `68`
- `SOURCE_CHANGE`: `NO`
