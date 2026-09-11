# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T07:19:22.347293+00:00`
- Run ID: `20260911T071920Z`
- Step: `INSPECT_REVIEW_UPDATE_STATEMENT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `REVIEW_UPDATE_STATEMENT_RESOLVED`
- Next gate: `VERIFY_LATEST_TYS_REVIEW_STATE_IN_OWNER`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `RESTART`: `NO`
- `REVIEW_REGISTER_ALREADY_WIRED`: `YES`
- `S1_LINE`: `151`
- `S1_SQL`: `SELECT_t.submission_id,_t.created_epoch_ms,_t.email,_t.technical_status,_t.benchtest_status,_c.name,_c.source_author,_COALESCE(_p.library_publication_status,_t.library_publication_`
- `S2_LINE`: `61`
- `S2_SQL`: `SELECT_submission_id,_candidate_id,_source_sha256,_library_review_allowed,_technical_status,_benchtest_status_FROM_test_your_script_submissions_v1_WHERE_submission_id=?_LIMIT_1`
- `SELECT_STATEMENT_COUNT`: `2`
- `SIX_METRICS_MAPPED`: `YES`
- `SOURCE_CHANGE`: `NO`
- `SQL_STATEMENT_COUNT`: `4`
- `TYS_E2E_PROVEN`: `YES`
- `U1_LINE`: `114`
- `U1_SQL`: `UPDATE_script_submission_policy_v1_SET_library_publication_status=?,_updated_epoch_ms=?_WHERE_source_sha256=?`
- `U1_TABLE`: `script_submission_policy_v1`
- `U2_LINE`: `129`
- `U2_SQL`: `UPDATE_test_your_script_submissions_v1_SET_library_publication_status=?,_updated_epoch_ms=?_WHERE_source_sha256=?`
- `U2_TABLE`: `test_your_script_submissions_v1`
- `UPDATE_STATEMENT_COUNT`: `2`
