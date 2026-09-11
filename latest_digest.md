# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T06:20:22.976162+00:00`
- Run ID: `20260911T062021Z`
- Step: `TRACE_TYS_REPORT_TOKEN_GUARD`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `REPORT_TOKEN_HELPER_IDENTIFIED`
- Next gate: `EXECUTE_EXISTING_TOKEN_HELPER_READONLY_DIAG`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `REPORT_ASSIGN_EXPR`: `private_report_projection_v14(sid,_raw_token)`
- `REPORT_ASSIGN_LINE`: `814`
- `RESTART`: `NO`
- `SOURCE_CHANGE`: `NO`
- `TOKEN_ASSIGN_EXPR`: `issue_private_report_access_token_v14(sid,_candidate_idcid,_source_sha256sha)`
- `TOKEN_ASSIGN_LINE`: `806`
- `TOKEN_HELPER`: `issue_private_report_access_token_v14`
- `TOKEN_HELPER_DB_FIELDS`: `benchtest_status_candidate_id_report_access_token_sha256_report_token_created_epoch_ms_run_id_source_sha256_submission_id_technical_status`
- `TOKEN_HELPER_EXISTS`: `YES`
- `TOKEN_HELPER_RETURN_COUNT`: `9`
- `TOKEN_HELPER_STATUS_LITERALS`: `BLOCKED_COMPLETE_ERROR_PASS_READY`
