# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-16T18:50:20.975436+00:00`
- Run ID: `20260916T185018Z`
- Step: `MAP_EXACT_PREFLIGHT_NOTE_MARKER_SEMANTICS`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `PREFLIGHT_NOTE_MARKER_SEMANTICS_MAPPED`
- Next gate: `REMOVE_ONLY_PREFLIGHT_MARKERS_FROM_CANDIDATE_NOTES`

## Facts

- `BODY_1`: `15049:current_shas,`
- `BODY_2`: `15074:if_&quot;notes&quot;_not_in_cols:`
- `BODY_3`: `15080:+&quot;,notes_FROM_candidates_&quot;`
- `BODY_4`: `15081:+&quot;WHERE_notes_LIKE_&quot;,`
- `BODY_5`: `15082:(&quot;TESTPINE_PREFLIGHT_V1=&quot;,),`
- `BODY_6`: `15085:processed=set()`
- `BODY_7`: `15086:passed=set()`
- `BODY_8`: `15090:r&quot;TESTPINE_PREFLIGHT_V1=&quot;`
- `CHECK_1`: `if_&#x27;notes&#x27;_not_in_cols:_return_(0,_0,_&#x27;NO_PROVEN_PREFLIGHT_MARKER&#x27;)`
- `CHECK_2`: `&#x27;notes&#x27;_not_in_cols`
- `CHECK_3`: `if_m.group(1).strip().upper()_==_&#x27;PASS&#x27;:_passed.add(source_sha)`
- `CHECK_4`: `m.group(1).strip().upper()_==_&#x27;PASS&#x27;`
- `CHECK_5`: `NONE`
- `CHECK_6`: `NONE`
- `CHECK_7`: `NONE`
- `CHECK_8`: `NONE`
- `CHECK_COUNT`: `4`
- `DB_WRITES`: `0`
- `FAILURE`: `NONE`
- `INTERNAL_RC`: `0`
- `MARKER_1`: `(:[rn])s*TESTPINE_PREFLIGHT_V1=([rn]+)`
- `MARKER_2`: `TESTPINE_PREFLIGHT_V1_CURRENT_EXECUTABLE_SOURCES`
- `MARKER_3`: `NO_PROVEN_PREFLIGHT_MARKER`
- `MARKER_4`: `PASS`
- `MARKER_5`: `TESTPINE_PREFLIGHT_V1=`
- `MARKER_6`: `NONE`
- `MARKER_7`: `NONE`
- `MARKER_8`: `NONE`
- `MARKER_COUNT`: `5`
- `READ_ONLY`: `YES`
- `RETURN_1`: `(len(processed),_len(passed),_&#x27;TESTPINE_PREFLIGHT_V1_CURRENT_EXECUTABLE_SOURCES&#x27;)`
- `RETURN_2`: `(0,_0,_&#x27;NO_CANDIDATES_TABLE&#x27;)`
- `RETURN_3`: `(0,_0,_&#x27;NO_SOURCE_SHA_IDENTITY&#x27;)`
- `RETURN_4`: `(0,_0,_&#x27;NO_PROVEN_PREFLIGHT_MARKER&#x27;)`
- `RETURN_5`: `NONE`
- `RETURN_COUNT`: `4`
