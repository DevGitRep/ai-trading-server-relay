# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T06:33:00.963197+00:00`
- Run ID: `20260911T063258Z`
- Step: `INSPECT_EMAIL_FUNCTION_LINES_795_806`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CONFIG_READY_CONTEXT_CAPTURED`
- Next gate: `IDENTIFY_ACTUAL_CONFIG_READY_SOURCE`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `CONFIG_READY_NAMED_EXPR_COUNT`: `0`
- `CONFIG_READY_NAME_HITS`: `0`
- `DB_WRITE`: `NO`
- `L795`: `finally:`
- `L796`: `con.close()`
- `L797`: `if_not_re.fullmatch(&#x27;[s][s].[s]&#x27;,_recipient):`
- `L798`: `_tys_set_email_state_v15(sid,_status&#x27;ERROR&#x27;,_error&#x27;INVALID_EMAIL&#x27;)`
- `L799`: `return_&#x27;status&#x27;:_&#x27;ERROR&#x27;,_&#x27;reason&#x27;:_&#x27;INVALID_EMAIL&#x27;`
- `L800`: `config___tys_email_config_v15()`
- `L801`: `if_not_config[&#x27;ready&#x27;]:`
- `L802`: `reason__&#x27;&#x27;.join(config[&#x27;missing&#x27;])`
- `L803`: `_tys_set_email_state_v15(sid,_status&#x27;CONFIG_REQUIRED&#x27;,_errorreason)`
- `L804`: `return_&#x27;status&#x27;:_&#x27;CONFIG_REQUIRED&#x27;,_&#x27;reason&#x27;:_reason`
- `L805`: `_tys_set_email_state_v15(sid,_status&#x27;SENDING&#x27;,_errorNone,_attemptedTrue)`
- `L806`: `token_result__issue_private_report_access_token_v14(sid,_candidate_idcid,_source_sha256sha)`
- `RESTART`: `NO`
- `SOURCE_CHANGE`: `NO`
