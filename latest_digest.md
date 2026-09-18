# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-18T23:49:40.407918+00:00`
- Run ID: `20260918T234938Z`
- Step: `DIAGNOSEFINAL257FAILURES`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXACTREMAININGFAILURESIDENTIFIED`
- Next gate: `PATCHSELECTORANDTESTISOLATION`

## Facts

- `CANDLE_DETAIL`: `AssertionError: &#x27;DB_WRITES=0&#x27; not found in &#x27;&#x27; AssertionError: &#x27;CROSSOVER&#x27; != &#x27;CANONICAL_TA_FALLBACK&#x27;`
- `COMMIT`: `NO`
- `DB_WRITE`: `NO`
- `DIRTY_COUNT`: `3`
- `HEAD`: `398294cb1bc9`
- `REPO_WRITE`: `NO`
- `RESTART`: `NO`
- `SEM_ERROR`: `Traceback (most recent call last): TypeError: select_recent.&lt;locals&gt;.identity() takes 3 positional arguments but 4 were given`
- `TARGET_FAILURES`: `test_candle_failure_is_classified_before_writes,test_cli_summary_always_write_and_dry_run_rejected,test_production_files_unchanged,test_readonly_selector_exact_canonical_order_and_`
- `V1_MARKERS`: `0`
- `V2_MARKERS`: `0`
