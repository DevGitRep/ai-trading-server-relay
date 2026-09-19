# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-19T18:00:11.303343+00:00`
- Run ID: `20260919T180009Z`
- Step: `MAPATBSIGNALSTOEXECUTION327`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `ATBSIGNALEXECUTIONPATHMAPPED`
- Next gate: `EXECUTEATBSUITENAMINGMIGRATION`

## Facts

- `CODE_WRITE`: `NO`
- `COMMIT`: `NO`
- `DB_WRITE`: `NO`
- `EXEC_1`: `SCORE=2:tools/atb_quant_engine/numba_multisignal.py:L26:run_multisignal_kernel(open_prices,_high,_low,_signal_bars,_signal_dirs,_atr_matrix,_config_atr_idx,_reward_r,_fee_rate,_size,_slippage_rate)`
- `EXEC_2`: `SCORE=2:tools/atb_quant_engine/portfolio.py:L207:asset_flow(close,_order_records)`
- `EXEC_3`: `SCORE=2:tools/atb_quant_engine/portfolio.py:L259:assets(close,_order_records)`
- `EXEC_CANDIDATE_COUNT`: `24`
- `HEAD`: `e40f9755c8a3`
- `PF_ATTRS`: ``
- `PF_ATTR_COUNT`: `0`
- `PF_CALL_1`: ``
- `PF_CALL_2`: ``
- `PF_CALL_3`: ``
- `PF_CALL_COUNT`: `0`
- `PUSH`: `NO`
- `RESTART`: `NO`
- `TESTRESULTS_FUNCTION`: `portfolio:L1156-L1248`
