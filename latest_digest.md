# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-08-27T21:28:53.346030+00:00`
- Run ID: `20260827T212851Z`
- Step: `RESOLVEINDICATORLABPERSISTENCEAUTHORITY_V1`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `INDICATOR_LAB_TEST_RUNS_DB_AUTHORITY_AMBIGUOUS`
- Next gate: `REVIEW_INDICATOR_LAB_DB_AUTHORITY_V1`

## Facts

- `ARTIFACTCOMMITTED`: `NO`
- `CALL01`: `L428:initialize_indicator_lab_v1()`
- `DB01`: `user_data/orderflow_dashboard/data/manual_support/pine_catalog_v1.db:pine_scripts`
- `DB02`: `user_data/orderflow_dashboard/data/manual_support/indicator_challenger_lab_v1.db:candidate_events,candidates,intake_jobs,test_runs`
- `DB03`: `user_data/orderflow_dashboard/data/manual_support/archive/indicator_challenger_lab_v1_PRE_VIPRASOL_DISCOVERY_V2_LIVE_20260825T111017Z.db:candidate_events,candidates,intake_jobs,tes`
- `DBACCESS`: `SCHEMA_ONLY`
- `DBMUTATION`: `NO`
- `INITCALLS`: `1`
- `INITCREATESTESTRUNS`: `YES`
- `INITDBREFS`: `0`
- `INITLINES`: `68-260`
- `INITSIG`: `initialize_indicator_lab_v1()`
- `NETWORKCALL`: `NO`
- `PERF`: `NO`
- `PINETSEXEC`: `NO`
- `READONLY`: `YES`
- `RELEVANTDBS`: `3`
- `RESULTROWSREAD`: `NO`
- `TESTRUNSDBS`: `2`
