# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-08-27T18:31:10.694837+00:00`
- Run ID: `20260827T183108Z`
- Step: `PINECATV5DEPENDENCYUSAGEREVIEW_V1`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `PINECAT_V5_DEPENDENCY_USAGE_REVIEW_COMPLETE`
- Next gate: `DECIDE_PINECAT_V5_SEMANTIC_RECOVERY_PATH_V1`

## Facts

- `ARTIFACTCOMMITTED`: `NO`
- `ATR_LENGTHLOADCOUNT`: `0`
- `ATR_MULTIPLIERLOADCOUNT`: `0`
- `BEARASSIGNCOUNT`: `1`
- `BEAREXPR`: `data[&#x27;close&#x27;].rolling(window_jurik_length).apply(lambda_x:_x.min()_if_x.min()_&lt;_x.max()_else_x.max())`
- `BULLASSIGNCOUNT`: `1`
- `BULLEXPR`: `data[&#x27;close&#x27;].rolling(window_jurik_length).apply(lambda_x:_x.max()_if_x.max()_&gt;_x.min()_else_x.min())`
- `DBACCESS`: `NO`
- `GENERATEDPYTHONEXEC`: `NO`
- `GENERATEDPYTHONIMPORT`: `NO`
- `JURIK_SOURCELOADCOUNT`: `0`
- `KWONLYCOUNT`: `17`
- `OLLAMACALL`: `NO`
- `PERF`: `NO`
- `READONLY`: `YES`
- `REQSTATEMENTCOUNT`: `0`
- `REQUIREDINARGS`: `YES`
- `TESTRUNS`: `NO`
- `WARMUP_BARSLOADCOUNT`: `0`
