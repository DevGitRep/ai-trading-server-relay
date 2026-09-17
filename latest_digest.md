# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-17T06:57:10.460392+00:00`
- Run ID: `20260917T065704Z`
- Step: `RESOLVE_ACTIVE_BENCHTEST_YEAR_LOADER`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `ACTIVE_YEAR_LOADER_AND_BENCHTEST_CALL_CHAIN_CONFIRMED`
- Next gate: `RUN_REAL_SOL_1M_YEAR_HYPOTHESIS_TO_QUANT_ACCEPTANCE`

## Facts

- `ACTIVE_BENCH_ENTRY`: `tools/atb_preflight_v2/orchestrator.py`
- `ACTIVE_BENCH_FILES`: `subscription_v1.py,shadow_ai_prospective_rotation_v23.py,indicator_lab_library_ui_v1.py,indicator_lab_tier_runtime_v1b`
- `ACTIVE_LOADER_CALL`: `tools/atb_preflight_v2/orchestrator.py:production.load_candles()`
- `ACTIVE_YEAR_LOADER`: `tools/legacy_disabled/resin_clean_cut_20260831T073405Z/pine_baseline_batch_200.py:load_candles()`
- `ATB_CHANGED`: `NO`
- `BACKUPS_EXCLUDED`: `YES`
- `CALL_CHAIN_CONFIRMED`: `YES`
- `DASHBOARD_RESTART`: `NO`
- `DB_WRITES`: `0`
- `FAILURE`: `NONE`
- `INTERNAL_RC`: `0`
- `LOADER_CALLS`: `tools/atb_preflight_v2/orchestrator.py:production.load_candles()`
- `LOADER_DEFS`: `lifecycle_shadow.py:_load_training_candles(pair_values,min_epoch,max_epoch),lifecycle_shadow.py:_load_cache_candles(pa`
- `MANUAL_SUPPORT_EXCLUDED`: `YES`
- `READY_FOR_REAL_YEAR_RUN`: `YES`
- `SOL_1M_REFS`: `pine_catalog_ingest_adapters_v1.py,test_your_script_v1.py,indicator_lab_v1.py,shadow_ai_prospective_challenger.py,pine`
- `VENV_EXCLUDED`: `YES`
- `YEAR_REFS`: `NONE`
