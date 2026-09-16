# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-16T15:34:34.365387+00:00`
- Run ID: `20260916T153432Z`
- Step: `INSPECT_ANALYZE_AND_RUNTIME_CANDIDATE_BOUNDARY`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `ANALYZE_AND_RUNTIME_CANDIDATE_FLOW_EXPOSED`
- Next gate: `INSTRUMENT_EXACT_CANDIDATE_BOUNDARY_FOR_31`

## Facts

- `ANALYZE_STMT_1`: `66:if_not_isinstance(source,_str)_or_not_source.strip():_raise_V2Error(&#x27;PINE_SOURCE_ERROR&#x27;)`
- `ANALYZE_STMT_2`: `68:source_=_source.removeprefix(&#x27;ufeff&#x27;).replace(&#x27;rn&#x27;,_&#x27;n&#x27;).replace(&#x27;r&#x27;,_&#x27;n&#x27;)`
- `ANALYZE_STMT_3`: `69:try:_parsed_=_parser(source)_except_Exception_as_exc:_raise_V2Error(exception_class(exc,_&#x27;PINE2AST_ENV_ERROR&#x27;))_from_None`
- `ANALYZE_STMT_4`: `73:try:_candidates_=_discover(source,_parsed[&#x27;ast&#x27;])_if_parsed[&#x27;ok&#x27;]_else_[]_except_Exception_as_exc:_raise_V2Error(exception_class(exc,_&#x27;ADAPTER_ERRO`
- `ANALYZE_STMT_5`: `77:outcome_=_{&#x27;status&#x27;:_None,_&#x27;parse_reason&#x27;:_parsed[&#x27;reason&#x27;],_&#x27;attempts&#x27;:_[],_&#x27;examined_lanes&#x27;:_list(LANES[:-1]),_&#x27;fallback_considered&#x27;:_False,_&#x27;sel`
- `ANALYZE_STMT_6`: `80:try:_runtime_=_runner(source,_candles)_except_Exception_as_exc:_raise_V2Error(exception_class(exc,_&#x27;RESIN_EXECUTION_ERROR&#x27;))_from_None`
- `ANALYZE_STMT_7`: `84:if_runtime.get(&#x27;kind&#x27;)_not_in_(&#x27;strategy&#x27;,_&#x27;indicator&#x27;):_outcome.update(status=&#x27;ERROR&#x27;,_reason=&#x27;RESIN_&#x27;_+_str(runtime.get(&#x27;stage&#x27;,_&#x27;UNKNOWN&#x27;)),_err`
- `ANALYZE_STMT_8`: `89:rescue_=_not_parsed[&#x27;ok&#x27;]_and_bool(parsed.get(&#x27;syntax_gap&#x27;))`
- `ANALYZE_STMT_COUNT`: `18`
- `FAILURE`: `NONE`
- `INTERNAL_RC`: `0`
- `READ_ONLY`: `YES`
- `RUNTIME_CALLS`: `Candidate,any,candidates.append,direction,enumerate,isinstance,len,output.get,result.get,viz.get`
- `RUNTIME_CALL_COUNT`: `10`
- `RUNTIME_LANES`: `EXPLICIT_SIGNAL`
- `RUNTIME_LANE_COUNT`: `1`
- `RUNTIME_RETURN_1`: `candidates`
- `RUNTIME_RETURN_COUNT`: `1`
- `RUNTIME_SIG`: `runtime_candidates(result,candles)`
- `RUNTIME_STMT_1`: `13:&#x27;Observe_author-labelled_outputs,_without_parsing_or_instrumenting_Pine.&#x27;`
- `RUNTIME_STMT_2`: `14:from_.adapter_import_Candidate,_direction`
- `RUNTIME_STMT_3`: `15:candidates_=_[]`
- `RUNTIME_STMT_4`: `16:viz_=_result.get(&#x27;viz&#x27;)_or_{}`
- `RUNTIME_STMT_5`: `17:for_family,_field_in_((&#x27;plots&#x27;,_&#x27;values&#x27;),_(&#x27;shapes&#x27;,_&#x27;condition&#x27;),_(&#x27;chars&#x27;,_&#x27;condition&#x27;)):_outputs_=_result.get(&#x27;plots&#x27;,_[])_if_family_==_&#x27;plots&#x27;`
- `RUNTIME_STMT_6`: `36:return_candidates`
- `RUNTIME_STMT_7`: `NONE`
- `RUNTIME_STMT_8`: `NONE`
- `RUNTIME_STMT_COUNT`: `6`
