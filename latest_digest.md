# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T15:19:48.643247+00:00`
- Run ID: `20260908T151946Z`
- Step: `READCHARTTIER`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CHARTTIERREAD`
- Next gate: `PATCHFREECHARTPROFILE`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `DB_WRITE`: `NO`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
- `TIER1`: `CHART 1873:@app.route( | 1874:&quot;/indicator-lab/strategy/&lt;candidate_id&gt;/bench-chart-data&quot;, | 1875:methods=[&quot;GET&quot;],`
- `TIER10`: `CHART 1900:/ &#x27;benchtest_market_candles_b577ee5771839c9aea350659027c8ff45e0af93eabb349b1d1266818857339fc_v1.json&#x27; |`
- `TIER11`: `CHART 1903:try: | 1904:_metrics = _report_metrics( | 1905:candidate_id,`
- `TIER12`: `CHART 1906:&quot;PRO&quot;, | 1907:)`
- `TIER13`: `CHART 1909:if not isinstance( | 1910:_metrics, | 1911:dict,`
- `TIER14`: `CHART 1912:): | 1913:return _jsonify( | 1914:{`
- `TIER15`: `CHART 1915:&quot;ok&quot;: False, | 1916:&quot;error&quot;: &quot;BenchTest mapping unavailable&quot;, | 1917:}`
- `TIER16`: `CHART 1918:), 404 | 1920:_indicator_id = str(`
- `TIER17`: `CHART 1921:_metrics.get( | 1922:&quot;candidate_id&quot; | 1923:)`
- `TIER18`: `CHART 1924:or &quot;&quot; | 1925:).strip()`
- `TIER19`: `CHART 1927:if not _indicator_id: | 1928:return _jsonify( | 1929:{`
- `TIER2`: `CHART 1876:) | 1877:def indicator_lab_report_bench_chart_data_v28c(candidate_id): | 1878:import json as _json`
- `TIER20`: `CHART 1930:&quot;ok&quot;: False, | 1931:&quot;error&quot;: &quot;Indicator identity unavailable&quot;, | 1932:}`
- `TIER21`: `CHART 1933:), 404`
- `TIER22`: `REPORT 2368:_indicator_lab_internal_preview_enabled() | 2369:and | 2370:_indicator_lab_internal_request_authorized`
- `TIER23`: `REPORT 2371:) | 2373:requested_tier = str(`
- `TIER24`: `REPORT 2374:_indicator_lab_requested_tier() | 2375:or &#x27;FREE&#x27; | 2376:).upper()`
- `TIER25`: `REPORT 2378:if ( | 2379:preview_authorized`
- `TIER26`: `REPORT 2380:and requested_tier | 2381:in { | 2382:&#x27;FREE&#x27;,`
- `TIER27`: `REPORT 2383:&#x27;PRO&#x27;, | 2384:&#x27;INTERNAL_ADMIN&#x27;, | 2385:}`
- `TIER3`: `CHART 1879:import sqlite3 as _sqlite3 | 1880:from pathlib import Path as _Path`
- `TIER4`: `CHART 1882:from flask import jsonify as _jsonify | 1883:from indicator_lab_library_ui_v1 import ( | 1884:load_repo`
- `TIER5`: `CHART 1885:) | 1887:_root = _Path(__file__).resolve().parent`
- `TIER6`: `CHART 1889:_db = ( | 1890:_root`
- `TIER7`: `CHART 1891:/ &quot;data&quot; | 1892:/ &quot;manual_support&quot; | 1893:/ &quot;indicator_challenger_lab_v1.db&quot;`
- `TIER8`: `CHART 1894:) | 1896:_cache = (`
- `TIER9`: `CHART 1897:_root | 1898:/ &quot;data&quot; | 1899:/ &quot;manual_support&quot;`
