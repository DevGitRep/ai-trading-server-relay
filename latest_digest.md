# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-08-30T20:27:06.423757+00:00`
- Run ID: `20260830T202704Z`
- Step: `INSPECT_EXACT_PREFLIGHT_COMMAND`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXACT_PREFLIGHT_COMMAND_STRUCTURE_READ`
- Next gate: `REPLAY_THIS_EXACT_COMMAND_FOR_IDENTIFIED_CANDIDATE`

## Facts

- `ARG0`: `str(_tp_node)`
- `ARG1`: `&#x27;--input-type=module&#x27;`
- `ARG2`: `&#x27;-e&#x27;`
- `ARG3`: `&#x27;import fs from &quot;node:fs&quot;;\nimport { pathToFileURL } from &quot;node:url&quot;;\n\nconst pinePath =`
- `ARG4`: `str(source_path)`
- `ARG5`: `_tp_data_tmp`
- `ARG6`: `&#x27;&lt;path&gt;&#x27;`
- `ARG7`: `NONE`
- `CAPTURE_OUTPUT_KW`: `NONE`
- `CODE_CHANGED`: `NO`
- `COMMAND_ELTS`: `7`
- `COMMAND_RESOLVED`: `YES`
- `CWD_KW`: `NONE`
- `DB_WRITE`: `NO`
- `ERROR`: `NONE`
- `JS_ARGV_INDEXES`: `1,2,3`
- `JS_CONSTRUCTOR`: `new Error(&quot;PINETS_CLASS_NOT_FOUND&quot;)`
- `JS_DATA_ARG`: `NONE`
- `JS_FOUND`: `YES`
- `JS_PINETS_IMPORT`: `NONE`
- `JS_SOURCE_ARG`: `NONE`
- `MASTER_UPDATED`: `NO`
- `PROCESS_FOUND`: `YES`
- `STDERR_KW`: `subprocess.PIPE`
- `STDOUT_KW`: `subprocess.PIPE`
- `SUBPROCESS_FOUND`: `YES`
- `SUBPROCESS_LINE`: `2816`
- `TEXT_KW`: `True`
