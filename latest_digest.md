# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T10:58:53.494734+00:00`
- Run ID: `20260908T105851Z`
- Step: `READLIBMETRICPATH`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `LIBMETRICPATHREAD`
- Next gate: `PATCHLIBMETRICPATH`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `BULK1`: `SELECT`
- `BULK2`: `indicator_id,`
- `BULK3`: `primary_max_drawdown_pct,`
- `BULK4`: `FROM indicator_pipeline_current`
- `BULK5`: `candidate_id = str(row[&quot;indicator_id&quot;])`
- `CARD1`: `Profit Factor=profit_factor`
- `CARD2`: `Net Return=net_return_pct`
- `CARD3`: `Max Drawdown=max_drawdown_pct`
- `CARD4`: `Win Rate=win_rate_pct`
- `CARD5`: `Trades=trade_count`
- `CARD6`: `Realistic Score=realistic_score`
- `DB_WRITE`: `NO`
- `KEY1`: `_bench_metrics_from_row_v25b:candidate_id`
- `KEY2`: `_bench_metrics_from_row_v25b:signal_mode`
- `KEY3`: `_bench_metrics_from_row_v25b:test_status`
- `KEY4`: `_bench_metrics_from_row_v25b:profit_factor`
- `KEY5`: `_bench_metrics_from_row_v25b:net_return_pct`
- `KEY6`: `_bench_metrics_from_row_v25b:max_drawdown_pct`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `OPTION1`: `realistic=Realistic Score - high to low`
- `OPTION2`: `profit=Profit Factor - high to low`
- `OPTION3`: `return=Net Return - high to low`
- `OPTION4`: `win=Win Rate - high to low`
- `OPTION5`: `NONE`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SORT1`: `def _card_sort_key(card):`
- `SORT2`: `&quot;realistic_score&quot;`
- `SORT3`: `&quot;net_return_pct&quot;`
- `SORT4`: `NONE`
- `SORT5`: `NONE`
- `SORT6`: `NONE`
- `SOURCE_CHANGE`: `NO`
