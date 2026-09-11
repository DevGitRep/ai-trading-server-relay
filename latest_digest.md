# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T07:06:59.897193+00:00`
- Run ID: `20260911T070657Z`
- Step: `INSPECT_EXISTING_INTERNAL_REVIEW_APPROVED_GATE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXISTING_REVIEW_AND_APPROVED_GATE_FOUND`
- Next gate: `MAP_TYS_COMPLETE_TO_EXISTING_REVIEW`

## Facts

- `APPROVED_HIT1`: `test_your_script_v1.py:filter_public_shas:51`
- `APPROVED_HIT2`: `test_your_script_v1.py:create_submission:121`
- `APPROVED_HIT3`: `internal_test_submissions_v1.py:register_internal_test_submissions_v1:21`
- `APPROVED_HIT4`: `internal_test_submissions_v1.py:internal_test_submissions:35`
- `APPROVED_HIT5`: `indicator_lab_conversion_result_commit_v1.py:commit_conversion_result:30`
- `APPROVED_HIT6`: `pine_catalog_conversion_execution_guard_v1.py:run_conversion_guard:343`
- `APPROVED_HIT7`: `.venv/lib/python3.12/site-packages/charset_normalizer/cd.py:characters_popularity_compare:193`
- `APPROVED_HIT8`: `.venv/lib/python3.12/site-packages/scipy/stats/tests/test_mgc.py:_simulations:76`
- `APPROVED_HIT_COUNT`: `13`
- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `RESTART`: `NO`
- `REVIEW_HIT1`: `test_your_script_v1.py:_ensure_tables:40`
- `REVIEW_HIT2`: `test_your_script_v1.py:filter_public_shas:51`
- `REVIEW_HIT3`: `test_your_script_v1.py:create_submission:121`
- `REVIEW_HIT4`: `internal_test_submissions_v1.py:register_internal_test_submissions_v1:21`
- `REVIEW_HIT5`: `internal_test_submissions_v1.py:internal_test_submissions:35`
- `REVIEW_HIT6`: `indicator_lab_v1.py:_indicator_lab_internal_preview_enabled:426`
- `REVIEW_HIT7`: `indicator_lab_v1.py:_indicator_lab_internal_request_authorized:446`
- `REVIEW_HIT8`: `indicator_lab_v1.py:_indicator_lab_requested_tier:474`
- `REVIEW_HIT_COUNT`: `4485`
- `SOURCE_CHANGE`: `NO`
- `TEST_SUBMISSION_HIT1`: `test_your_script_v1.py:_benchtest_preconditions:404`
- `TEST_SUBMISSION_HIT2`: `test_your_script_v1.py:_tys_ensure_email_columns_v15:657`
- `TEST_SUBMISSION_HIT3`: `test_your_script_v1.py:_tys_set_email_state_v15:665`
- `TEST_SUBMISSION_HIT4`: `test_your_script_v1.py:_deliver_completed_report_email_v15:751`
- `TEST_SUBMISSION_HIT5`: `test_your_script_v1.py:_tys_ensure_private_report_columns_v14:846`
- `TEST_SUBMISSION_HIT6`: `test_your_script_v1.py:issue_private_report_access_token_v14:854`
- `TEST_SUBMISSION_HIT7`: `test_your_script_v1.py:revoke_private_report_access_token_v14:901`
- `TEST_SUBMISSION_HIT8`: `test_your_script_v1.py:private_report_projection_v14:918`
- `TEST_SUBMISSION_HIT_COUNT`: `10`
- `TYS_E2E_PROVEN`: `YES`
