# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-15T08:10:36.743757+00:00`
- Run ID: `20260915T081014Z`
- Step: `COMPARE_PRODUCTION_AND_WORKTREE_IMPORT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `IMPORT_RESULT_NEEDS_TARGETED_FIX`
- Next gate: `INSPECT_IMPORT_DIFFERENCE`

## Facts

- `CANDIDATE_COUNT`: `1`
- `PRODUCTION_GIT_DIRTY`: `0`
- `PROD_ERROR`: `sqlite3.OperationalError: database is locked`
- `PROD_ERROR_CLASS`: `SQLITE_ERROR`
- `PROD_IMPORT_RC`: `1`
- `WORK_ERROR`: `RuntimeError: MANIFEST_MISSING`
- `WORK_ERROR_CLASS`: `RUNTIME_ERROR`
- `WORK_IMPORT_RC`: `1`
