# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T10:51:45.564812+00:00`
- Run ID: `20260908T105143Z`
- Step: `READLIBSORTPATH`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `LIBSORTPATHREAD`
- Next gate: `PATCHLIBSORTPATH`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `CTX1`: `LIB:147:score = metrics.get( | &quot;realistic_score&quot; | )`
- `CTX2`: `LIB:196:) | win_rate_pct = _num( | row[&quot;win_rate_pct&quot;] | )`
- `CTX3`: `LIB:197:win_rate_pct = _num( | row[&quot;win_rate_pct&quot;] | )`
- `CTX4`: `LIB:200:) | realistic_score = _num( | row[&quot;realistic_score&quot;] | )`
- `DB_WRITE`: `NO`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `OPTION1`: `realistic=Realistic Score - high to low`
- `OPTION2`: `profit=Profit Factor - high to low`
- `OPTION3`: `return=Net Return - high to low`
- `OPTION4`: `win=Win Rate - high to low`
- `OPTION5`: `NONE`
- `OWNER1`: `LIB:_metric_preference:127`
- `OWNER2`: `LIB:_bench_metrics_from_row_v25b:180`
- `OWNER3`: `LIB:_empty_metrics:383`
- `OWNER4`: `LIB:_card_sort_key:525`
- `PREFLIGHT_RERUN`: `NO`
- `QUICK`: `ok`
- `REALSORT`: `realistic`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
- `WINSORT`: `win`
