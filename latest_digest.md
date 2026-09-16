# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-16T15:11:48.097451+00:00`
- Run ID: `20260916T151146Z`
- Step: `MAP_EXACT_EXISTING_V2_API_SHAPES`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `V2_EXISTING_API_SHAPES_MAPPED`
- Next gate: `RUN_RESCUE_USING_EXACT_EXISTING_CALL_FLOW`

## Facts

- `ANALYZE_PROVIDER_CALL`: `parser:1:0`
- `ANALYZE_RUNTIME_CALL`: `runner:2:0`
- `ANALYZE_SIG`: `analyze(source,candles,parser=parse,runner=resin,validator=validate,recognizer=recognize)`
- `CLI_IMPORTS`: `atb_preflight_v2.orchestrator:main`
- `CLI_MAIN_CALLS`: `NONE`
- `CLI_MAIN_SIG`: `NONE`
- `FAILURE`: `NONE`
- `INTERNAL_RC`: `0`
- `PARSE_LOCAL_SIG`: `parse_local(source)`
- `READ_ONLY`: `YES`
- `RUNTIME_FUNCS`: `probe_source,resin,runtime_candidates,validate,validate_runtime`
- `RUNTIME_PRIMARY_CALLS`: `tempfile.TemporaryDirectory:0:1,Path:1:0,pine.write_text:1:1,data.write_text:1:1,subprocess.run:1:5,json.dumps`
- `RUNTIME_PRIMARY_SIG`: `resin(source,candles)`
- `SELECT_PROD_CALLS`: `production.load_testpine:0:0`
- `SELECT_RECENT_CALLS`: `load_script:1:0,production.load_testpine:0:0,sqlite3.connect:1:1,conn.execute:1:0,SimpleNamespace:0:2,tp.selec`
- `SELECT_RECENT_SIG`: `select_recent(count,production=None,testpine=None)`
