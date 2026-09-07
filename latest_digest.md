# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-07T01:37:48.710590+00:00`
- Run ID: `20260907T013746Z`
- Step: `PROVEN_LOAD_LIBRARY_CARDS_READ`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `PROVEN_CARD_SOURCE_SCORE_MAPPING_CAPTURED`
- Next gate: `MINIMAL_REALISTIC_SCORE_CARD_SOURCE_PATCH`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `CHANGES_MADE`: `NO`
- `FUNCTION_FOUND`: `YES`
- `FUNCTION_RANGE`: `L916-1229`
- `HAS_BENCHTEST_RESULTS`: `NO`
- `HAS_BENCH_SCORE_V2`: `NO`
- `HAS_REALISTIC_SCORE`: `NO`
- `MASTER_READ`: `YES`
- `RESTART`: `NO`
- `SEAM_1`: `L916:def load_library_cards(`
- `SEAM_2`: `L940:cards = []`
- `SEAM_3`: `L957:from test_your_script_v1 import (`
- `SEAM_4`: `L970:# source_sha_cache_v1 already provides source_sha256.`
- `SEAM_5`: `L981:public_source_shas = set(`
- `SEAM_6`: `L984:str(item[&quot;source_sha256&quot;])`
- `SEAM_7`: `L986:if item[&quot;source_sha256&quot;]`
- `SEAM_8`: `L994:if item[&quot;source_sha256&quot;]:`
