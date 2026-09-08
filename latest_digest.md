# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T14:55:46.143975+00:00`
- Run ID: `20260908T145544Z`
- Step: `READCHARTIDENTITY`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CHARTIDENTITYREAD`
- Next gate: `PATCHFREECHARTPROFILE`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `DB_WRITE`: `NO`
- `ID1`: `CHART 1980:(_indicator_id,), | 1981:).fetchone() | 1983:if _run is None:`
- `ID10`: `CHART 2016:&quot;error&quot;: &quot;Chart artifact unavailable&quot;, | 2017:} | 2018:), 404`
- `ID11`: `CHART 2020:_rows = _con.execute( | 2021:&quot;&quot;&quot; | 2022:SELECT raw_json | 2023:FROM benchtest_trades_v1`
- `ID12`: `CHART 2024:WHERE run_id=? | 2025:AND candidate_id=? | 2026:ORDER BY CAST(trade_no AS INTEGER) | 2027:&quot;&quot;&quot;,`
- `ID13`: `CHART 2028:( | 2029:_artifact_run, | 2030:_indicator_id, | 2031:),`
- `ID14`: `CHART 2032:).fetchall() | 2034:_con.close()`
- `ID15`: `CHART 2036:_trades = [] | 2038:for _row in _rows: | 2039:try:`
- `ID16`: `CHART 2040:_trade = _json.loads( | 2041:_row[&quot;raw_json&quot;] | 2042:) | 2043:except Exception:`
- `ID17`: `CHART 2044:continue | 2046:if not isinstance( | 2047:_trade,`
- `ID18`: `CHART 2048:dict, | 2049:): | 2050:continue`
- `ID19`: `CHART 2052:if ( | 2053:str( | 2054:_trade.get( | 2055:&quot;benchmark_mode&quot;`
- `ID2`: `CHART 1984:_con.close() | 1986:return _jsonify( | 1987:{`
- `ID20`: `CHART 2056:) | 2057:or &quot;&quot; | 2058:).strip() | 2059:!= _primary_mode`
- `ID21`: `CHART 2060:): | 2061:continue | 2063:_trades.append(`
- `ID22`: `CHART 2064:_trade | 2065:) | 2067:_expected = int(`
- `ID23`: `CHART 2068:_run[ | 2069:&quot;primary_trade_count&quot; | 2070:] | 2071:or 0`
- `ID24`: `CHART 2072:) | 2074:if len(_trades) != _expected: | 2075:return _jsonify(`
- `ID3`: `CHART 1988:&quot;ok&quot;: False, | 1989:&quot;error&quot;: &quot;No current BenchTest&quot;, | 1990:} | 1991:), 404`
- `ID4`: `CHART 1993:_payload = _json.loads( | 1994:_run[&quot;payload&quot;] | 1995:)`
- `ID5`: `CHART 1997:_artifact_run = ( | 1998:_payload.get( | 1999:&quot;run_id&quot;`
- `ID6`: `CHART 2000:) | 2001:) | 2003:_primary_mode = str(`
- `ID7`: `CHART 2004:_run[ | 2005:&quot;primary_benchmark_mode&quot; | 2006:] | 2007:or &quot;&quot;`
- `ID8`: `CHART 2008:).strip() | 2010:if not _artifact_run: | 2011:_con.close()`
- `ID9`: `CHART 2013:return _jsonify( | 2014:{ | 2015:&quot;ok&quot;: False,`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
