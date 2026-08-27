# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-08-27T21:42:05.888413+00:00`
- Run ID: `20260827T214203Z`
- Step: `RESOLVEJURIKINDICATORLABCANDIDATE_V1`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `JURIK_NOT_YET_REGISTERED_IN_ACTIVE_INDICATOR_LAB`
- Next gate: `REGISTER_JURIK_USING_EXISTING_INDICATOR_LAB_PATH_AND_START_DISCOVERY_V1`

## Facts

- `ARTIFACTCOMMITTED`: `NO`
- `CANDIDATECOLS`: `candidate_id,created_epoch_ms,updated_epoch_ms,intake_method,name,family,target_market,timeframes_json,source_url,source_author,source_license,source_sha256,pine_version,pine_source,status`
- `DBACCESS`: `IDENTITY_ONLY`
- `DBMUTATION`: `NO`
- `EXACTMATCHES`: `0`
- `EXISTINGIDFUNCS`: `2`
- `FROM_NAME`: `ICL_NAME_B3F6955D7B2977D1`
- `FROM_SOURCE`: `ICL_SRC_FD95B3D18254030E`
- `FUNC01`: `_candidate_id_for_name(name)`
- `FUNC02`: `_candidate_id_for_source(source)`
- `FUNC03`: `_list_candidates()`
- `FUNC04`: `_get_candidate(candidate_id)`
- `FUNC05`: `register_indicator_lab_routes(app)`
- `NETWORKCALL`: `NO`
- `PAIR`: `SOLUSDT`
- `PERF`: `NO`
- `PINETSEXEC`: `NO`
- `READONLY`: `YES`
- `REGFUNCS`: `5`
- `RESULTROWSREAD`: `NO`
- `TIMEFRAME`: `1m`
