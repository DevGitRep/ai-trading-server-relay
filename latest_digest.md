# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-16T15:24:05.145748+00:00`
- Run ID: `20260916T152402Z`
- Step: `MAP_PARSE_LOCAL_SYMBOL_ORIGINS`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `PARSE_LOCAL_SYMBOL_ORIGINS_MAPPED`
- Next gate: `USE_EXACT_EXISTING_PROVIDER_ROUTE`

## Facts

- `AST_TO_JSON_ORIGIN`: `UNRESOLVED`
- `CALL1_NAME`: `ParseOptions`
- `CALL1_ORIGIN`: `LOCAL_IMPORT:pine2ast.ParseOptions`
- `CALL2_NAME`: `RuntimeError`
- `CALL2_ORIGIN`: `BUILTIN`
- `CALL3_NAME`: `any`
- `CALL3_ORIGIN`: `BUILTIN`
- `CALL4_NAME`: `ast_to_dict`
- `CALL4_ORIGIN`: `UNRESOLVED`
- `CALL5_NAME`: `bool`
- `CALL5_ORIGIN`: `BUILTIN`
- `CALL6_NAME`: `int`
- `CALL6_ORIGIN`: `BUILTIN`
- `CALL7_NAME`: `parse_code`
- `CALL7_ORIGIN`: `LOCAL_IMPORT:pine2ast.parse_code`
- `CALL8_NAME`: `re.search`
- `CALL8_ORIGIN`: `IMPORT:re`
- `FAILURE`: `NONE`
- `INTERNAL_RC`: `0`
- `LOCAL_IMPORT_COUNT`: `7`
- `LOCAL_IMPORT_SAMPLE`: `ParseOptions=pine2ast.ParseOptions`
- `PARSE_CALLS`: `strip,re.search,parse_code,any,bool,RuntimeError,revision.startswith,RuntimeError,int,ParseOptions,ast_to_dict,RuntimeEr`
- `PARSE_CALL_COUNT`: `15`
- `PARSE_CODE_ORIGIN`: `LOCAL_IMPORT:pine2ast.parse_code`
- `PARSE_OPTIONS_ORIGIN`: `LOCAL_IMPORT:pine2ast.ParseOptions`
- `READ_ONLY`: `YES`
