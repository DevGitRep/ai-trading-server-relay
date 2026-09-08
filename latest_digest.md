# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T06:21:30.224694+00:00`
- Run ID: `20260908T062128Z`
- Step: `READBENCHSTATWIRING`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `BENCHSTATWIRINGREAD`
- Next gate: `PATCHBENCHSTAT`

## Facts

- `ASSIGN_TARGET`: `bench,bench_semantics`
- `BENCHTEST_RERUN`: `NO`
- `BENCH_ASSIGN`: `( bench, bench_semantics, )=_indicator_library_ui_v2_benchtest( con, tables, current_shas, )`
- `BENCH_EXPR`: `&quot;benchtest_total&quot;=&gt;bench | &quot;benchtest_semantics&quot;=&gt;bench_semantics`
- `DB_WRITE`: `NO`
- `HELPER_RETURN`: `UNKNOWN`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `SOURCE_CHANGE`: `NO`
