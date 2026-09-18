# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-18T18:46:16.813290+00:00`
- Run ID: `20260918T184614Z`
- Step: `INSPECTACTIVESELECTUNTESTED222`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `ACTIVESELECTUNTESTEDREAD`
- Next gate: `EXPLAINWHY81NOTSELECTED`

## Facts

- `COMMIT`: `NO`
- `DB_WRITE`: `NO`
- `DEF_END`: `265`
- `DEF_LINE`: `168`
- `HEAD`: `398294cb1bc9`
- `LOGIC1`: `168:def select_untested(count, order):`
- `LOGIC2`: `192:SELECT x.rowid`
- `LOGIC3`: `194:WHERE x.script_id_part:s.script_id_part`
- `LOGIC4`: `195:ORDER BY`
- `LOGIC5`: `198:LIMIT 1`
- `LOGIC6`: `206:ORDER BY`
- `LOGIC7`: `226:if already_tested(conn, sha):`
- `LOGIC8`: `229:candidate_id : ensure_candidate(`
- `LOGIC_FACTS`: `13`
- `REPO_CLEAN`: `YES`
- `REPO_WRITE`: `NO`
- `RESTART`: `NO`
