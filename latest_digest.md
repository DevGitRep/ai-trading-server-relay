# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T11:22:06.300318+00:00`
- Run ID: `20260911T112204Z`
- Step: `CONFIRM_HELPER_METRICS_DICT_CREATION`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `ALL_THREE_HELPERS_CONFIRMED_MISSING_REVIEW_METRIC_KEYS`
- Next gate: `PATCH_ONLY_UPSTREAM_HELPER_METRIC_OUTPUTS`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `HELPER1`: `_v2_signal_flip`
- `HELPER1_CREATE1`: `L2461:KEYS=NONE:_v2_stats(_starting_equity=start,_ending_equity=ending,_equity_curve=curve,_trade_rows=trades,_exposure_b`
- `HELPER1_CREATION_COUNT`: `1`
- `HELPER1_MISSING`: `profit_factor,net_return_pct,max_drawdown_pct,win_rate_pct,trade_count`
- `HELPER1_PRESENT`: `NONE`
- `HELPER2`: `_v2_indicator_atr_1_1_5`
- `HELPER2_CREATE1`: `L3016:KEYS=NONE:_v2_stats(_starting_equity=start,_ending_equity=ending,_equity_curve=curve,_trade_rows=trades,_exposure_b`
- `HELPER2_CREATION_COUNT`: `1`
- `HELPER2_MISSING`: `profit_factor,net_return_pct,max_drawdown_pct,win_rate_pct,trade_count`
- `HELPER2_PRESENT`: `NONE`
- `HELPER3`: `_v2_native_strategy`
- `HELPER3_CREATE1`: `L3292:KEYS=NONE:_v2_stats(_starting_equity=initial,_ending_equity=ending,_equity_curve=curve,_trade_rows=rows,_exposure_b`
- `HELPER3_CREATION_COUNT`: `1`
- `HELPER3_MISSING`: `profit_factor,net_return_pct,max_drawdown_pct,win_rate_pct,trade_count`
- `HELPER3_PRESENT`: `NONE`
- `RESTART`: `NO`
- `SOURCE_CHANGE`: `NO`
