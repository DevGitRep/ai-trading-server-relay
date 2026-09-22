# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-22T09:49:00.458449+00:00`
- Run ID: `20260922T094858Z`
- Step: `CASE4PREFLIGHTRUNTIME`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CASE4_PREFLIGHT_RUNTIME_REFERENCES_RECOVERED`
- Next gate: `FINALIZE_CASE4_OR_INSPECT_DIRECT_RUNTIME`

## Facts

- `DASHBOARD_RESTART`: `NO`
- `F1`: `1:#!ROOT/freqtrade-venv/bin/python`
- `F10`: `31: str(TESTPINE),`
- `F11`: `35: loader.exec_module(mod)`
- `F12`: `42: for r in conn.execute(&quot;PRAGMA table_info(candidates)&quot;)`
- `F13`: `55: row   conn.execute(`
- `F14`: `79: raise RuntimeError(&quot;canonical SOL 1m dataset not found&quot;)`
- `F15`: `118: row   conn.execute(`
- `F16`: `131: raise RuntimeError(`
- `F17`: `146:def _quant_runtime_result(plots, candles):`
- `F18`: `148: Runtime-success quant preflight.`
- `F19`: `150: The quant layer executes only inside the pinned isolated`
- `F2`: `11:import subprocess`
- `F20`: `151: mlfinpy runtime. Resin runtime success remains PASS.`
- `F21`: `154: import subprocess`
- `F22`: `157: qpy   dash / &#x27;runtime&#x27; / &#x27;mlfinpy_v0_1_2&#x27; / &#x27;.venv&#x27; / &#x27;bin&#x27; / &#x27;python&#x27;`
- `F23`: `159: return (&#x27;PASS&#x27;, &#x27;RUNTIME_PASS_QUANT_RUNTIME_UNAVAILABLE&#x27;)`
- `F24`: `160: worker   &#x27;\nimport json\nimport math\nimport sys\n\nimport numpy as np\nimport pandas as pd\n\nfrom mlfinpy.filters import (\n cusum_filter,\n z_score_filter,\n)\nfrom mlfinpy.labeling`
- `F25`: `162: proc   subprocess.run([str(qpy), &#x27;-c&#x27;, worker], input json.dumps({&#x27;plots&#x27;: plots, &#x27;candles&#x27;: candles}), stdout subprocess.PIPE, stderr subprocess.PIPE, text True, timeout 120)`
- `F26`: `164: return (&#x27;PASS&#x27;, &#x27;RUNTIME_PASS_QUANT_SUBPROCESS_ERROR:&#x27; + type(exc).__name__)`
- `F27`: `166: return (&#x27;PASS&#x27;, &#x27;RUNTIME_PASS_QUANT_SUBPROCESS_FAILED&#x27;)`
- `F28`: `169: return (str(answer.get(&#x27;status&#x27;, &#x27;PASS&#x27;)), str(answer.get(&#x27;detail&#x27;, &#x27;RUNTIME_PASS_QUANT_RESULT_MISSING&#x27;)))`
- `F29`: `171: return (&#x27;PASS&#x27;, &#x27;RUNTIME_PASS_QUANT_RESULT_PARSE_FAILED&#x27;)`
- `F3`: `18:TESTPINE   DASH / &quot;tools/testpine&quot;`
- `F30`: `174: from atb_quant_engine.pine_parameter_overrides import apply_numeric_pine_overrides`
- `F4`: `20:NODE   DASH / &quot;runtime/nodejs/v22.23.2/bin/node&quot;`
- `F5`: `23:PREFLIGHT_MARKER   &quot;TESTPINE_PREFLIGHT_V1:&quot;`
- `F6`: `24:PREFLIGHT_AT   &quot;TESTPINE_PREFLIGHT_V1_AT &quot;`
- `F7`: `25:PREFLIGHT_DETAIL   &quot;TESTPINE_PREFLIGHT_V1_DETAIL &quot;`
- `F8`: `28:def load_testpine():`
- `F9`: `30: &quot;_canonical_testpine&quot;,`
- `HEAD`: `939755327f6d`
- `MATCH_COUNT`: `80`
- `PRODUCTION_CODE_WRITES`: `0`
- `PRODUCTION_DB_WRITES`: `0`
- `REPO_CLEAN`: `YES`
