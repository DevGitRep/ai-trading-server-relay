# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-07T14:28:07.513252+00:00`
- Run ID: `20260907T142805Z`
- Step: `READSORTENTITLEMENT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `BAREAPISMOKEMAYBENONENTITLEDSORT`
- Next gate: `TESTSORTWITHSAMEENTITLEMENTASUI`

## Facts

- `APISORT`: `realistic`
- `APITIER`: `FREE`
- `BENCHTEST_RERUN`: `NO`
- `CHANGES_MADE`: `NO`
- `DB_WRITE`: `NO`
- `DISPLAYLINE`: `645`
- `ENTITLEEXPR`: `entitled = tier in { &quot;PRO&quot;, &quot;INTERNAL_ADMIN&quot;, }`
- `ENTITLELINE`: `594`
- `HTTP`: `200`
- `MASTER_READ`: `YES`
- `NOTENTITLED`: `YES`
- `PAGE1SCORED`: `0`
- `PAGECALL`: `_indicator_lab_library_page_v26( cards, tier, q=request.args.get( &quot;q&quot;, &quot;&quot;, ), sort_key=request.args.get( &quot;sort&quot;, &quot;r`
- `PAGECALLLINE`: `1793`
- `PREFLIGHT_RERUN`: `NO`
- `QUICK`: `ok`
- `RESTART`: `NO`
- `SCORED`: `16`
- `SOURCE_CHANGE`: `NO`
- `TIERNODEN`: `7`
- `TIERSEM1`: `_indicator_lab_requested_tier()`
- `TOPLEVELSCORE`: `YES`
