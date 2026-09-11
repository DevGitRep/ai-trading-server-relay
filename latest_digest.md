# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T09:56:36.448731+00:00`
- Run ID: `20260911T095634Z`
- Step: `MAP_EXACT_REVIEW_CANDIDATE_ALIAS_INSERTION`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXACT_REVIEW_SELECT_ALIAS_INSERTION_POINT_FOUND`
- Next gate: `PATCH_ONLY_ADD_TYS_CANDIDATE_ID_ALIAS`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `QUERY_HIT_COUNT`: `9`
- `QUERY_LINE1`: `131:UPDATE_test_your_script_submissions_v1`
- `QUERY_LINE2`: `151:rows_=_con.execute(`
- `QUERY_LINE3`: `153:SELECT`
- `QUERY_LINE4`: `154:t.submission_id,`
- `QUERY_LINE5`: `175:FROM_test_your_script_submissions_v1_t`
- `QUERY_LINE6`: `177:JOIN_candidates_c`
- `QUERY_LINE7`: `178:ON_c.candidate_id=t.candidate_id`
- `QUERY_LINE8`: `184:ON_pi.legacy_candidate_id=t.candidate_id`
- `QUERY_LINE9`: `188:SELECT_v.version_id`
- `RESTART`: `NO`
- `RUNTIME_MISSING_KEY`: `candidate_id`
- `SELECT_HAS_CANDIDATE_ALIAS`: `NO`
- `SELECT_HAS_T_CANDIDATE_ID`: `YES`
- `SELECT_HAS_T_SUBMISSION_ID`: `YES`
- `SOURCE_CHANGE`: `NO`
