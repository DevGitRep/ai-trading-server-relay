# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-19T05:54:55.459708+00:00`
- Run ID: `20260919T055453Z`
- Step: `CANARYWRITEFORENSICS276`
- Status: `FAIL`
- Exit code: `0`
- Verdict: `FORENSICSFAILED`
- Next gate: `STOP`

## Facts

- `DB_WRITE`: `NO`
- `ERROR`: `PERSIST_SIGNATURE=(item, result) PERSIST_SOURCE=def persist_v2_result(item, result): status = ( &quot;PASS&quot; if isinstance(result, dict) and result.get(&quot;status&quot;) == &quot;BENCHTEST_READY_SHADOW&quot; else &quot;FAIL&quot; ) _p`
- `REPO_WRITE`: `NO`
- `RESTART`: `NO`
