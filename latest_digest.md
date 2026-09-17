# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-17T21:21:08.900090+00:00`
- Run ID: `20260917T212106Z`
- Step: `EXACTRESINOVERRIDEPOINT31`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `RESINOVERRIDEPOINTEXACTLYIDENTIFIED`
- Next gate: `BUILDPARAMETEROVERRIDEADAPTER`

## Facts

- `CALL`: `CALL=1074|main|_persist_resin_artifact_by_source(source, _resin_artifact)`
- `CALL_OWNER`: `main`
- `DB_WRITE`: `NO`
- `HEAD`: `2045f91959b7`
- `PERSIST_LINES`: `796-826`
- `PERSIST_SIG`: `source, artifact`
- `REPO_CLEAN`: `YES`
- `RESTART`: `NO`
- `SUBPROCESS1`: `SUBPROCESS=162|_quant_runtime_result|subprocess.run([str(qpy), &#x27;-c&#x27;, worker], input=json.dumps({&#x27;plots&#x27;: plots, &#x27;candles&#x27;: candles}), stdout=subprocess.PIPE, stderr=subprocess.PIPE, text=True, timeout=120)`
- `SUBPROCESS1_OWNER`: `_quant_runtime_result`
- `SUBPROCESS2`: `SUBPROCESS=270|run_preflight|_subprocess.run([str(_node), str(_adapter), str(_package), str(_pine), str(_data), str(_viz)], stdout=_subprocess.PIPE, stderr=_subprocess.PIPE, text=True, timeout=180)`
- `SUBPROCESS2_OWNER`: `run_preflight`
