# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T07:39:30.123785+00:00`
- Run ID: `20260908T073928Z`
- Step: `READREPORTLOCALS`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `REPORTLOCALSREAD`
- Next gate: `PATCHREPORTANDCHART`

## Facts

- `ASSIGN_HEAD`: `tier = str( effective_tier or &quot;FREE&quot; ).upper() | conn = sqlite3.connect( DB ) | conn.row_factory = sqlite3.Row`
- `ASSIGN_N`: `3`
- `BENCHTEST_RERUN`: `NO`
- `BEST_ARGS`: `conn,candidate_ids`
- `BEST_CALL`: `_best_metrics( conn, candidate_ids, )`
- `BEST_OWNER`: `metrics`
- `CAND_CALL`: `_candidate_ids( conn, sha, row[&quot;chart_url&quot;], )`
- `CAND_OWNER`: `candidate_ids`
- `CANON_HELPERS`: `YES`
- `CONNECT_CALL`: `sqlite3.connect( DB )`
- `CONNECT_OWNER`: `conn`
- `DB_WRITE`: `NO`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
