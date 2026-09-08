# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T08:14:07.518197+00:00`
- Run ID: `20260908T081405Z`
- Step: `READTRADELEDGER`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `TRADELEDGERCONTRACTREAD`
- Next gate: `PATCHREPORTV2`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `CONTRACT`: `TEXT24`
- `DB_WRITE`: `NO`
- `ENDTEST`: `D2:primary,secondary`
- `EVIDENCE`: `D4:evidence,mode,primary,secondary`
- `MARKER`: `t=_epoch_seconds( trade.get( &quot;Exit Timestamp&quot; ) )|_epoch_seconds( trade.get( &quot;Exit Timestamp&quot; ) )|trade.get( &quot;Exit Timestamp&quot; )`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `OLDJSON`: `NONE`
- `OLDKEYS`: `Avg Entry Price,Avg Exit Price,Entry Timestamp,Exit Timestamp,candles,market_data_sha256,plots_json,raw_json,run_id,source_candle_count,tested_at,trade_no`
- `PREFLIGHT_RERUN`: `NO`
- `QUICK`: `ok`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
- `TOP1`: `dataset_actual_candles=INT`
- `TOP2`: `dataset_expected_candles=INT`
- `TOP3`: `end_of_test_json=D2:primary,secondary`
- `TOP4`: `long_signal_count=INT`
- `TOP5`: `losing_trades=INT`
- `TRADELIST`: `NONE`
- `TRADELISTN`: `0`
- `TRADES`: `8`
