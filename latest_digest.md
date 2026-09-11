# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T13:25:32.050802+00:00`
- Run ID: `20260911T132529Z`
- Step: `VERIFY_ROW41_IN_LIBRARY_ROWS`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `ROW41_MISSING_FROM_LIBRARY_ROWS`
- Next gate: `FIX_ONLY_LIBRARY_ROWS_SOURCE_FILTER`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `LIBRARY_ROWS_COUNT`: `9294`
- `LIBRARY_ROWS_TRACE_COUNT`: `8`
- `RESTART`: `NO`
- `ROW41_FOUND_BY_CANDIDATE`: `NO`
- `ROW41_FOUND_BY_SHA`: `NO`
- `SOURCE_CHANGE`: `NO`
- `SRC1`: `L47:SELECT`
- `SRC2`: `L57:sc.source_sha256_AS_source_sha256,`
- `SRC3`: `L62:FROM_scripts_s`
- `SRC4`: `L64:JOIN_sources_so`
- `SRC5`: `L66:SELECT_x.rowid`
- `SRC6`: `L67:FROM_sources_x`
- `SRC7`: `L77:LIMIT_1`
- `SRC8`: `L80:LEFT_JOIN_source_sha_cache_v1_sc`
