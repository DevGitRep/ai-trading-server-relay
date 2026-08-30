# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-08-30T05:24:57.518584+00:00`
- Run ID: `20260830T052455Z`
- Step: `READ_PROCESS_SOURCE_LIBRARY_ENTRY_PATH`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CANONICAL_ENTRY_PATH_READ`
- Next gate: `IDENTIFY_EXISTING_LIBRARY_BRANCH`

## Facts

- `CODE_CHANGED`: `NO`
- `DB_WRITE`: `NO`
- `ERROR`: `NONE`
- `FIRST_ASSIGNS`: `2618:url = ( item.get( _source_url_ ) or item.get( _url_ ) or _ )|2628:provider = ( item.get( _provider_ ) or _ )|2642:acquisition = acquisition_for_url( url )`
- `FIRST_RETURNS`: `2635:if ( not url or _/script/_ not in url ): return False|2646:if acquisition is None: source_id = worker.source_id_for_url( provider or _TRADINGVIEW_PUBLIC_, url,|2688:if acquisition is None: return False`
- `LIBRARY_REFS`: `2881:TESTPINE_PREFLIGHT_PAIR=Buy/Sell|2759:TESTPINE_PREFLIGHT_STATUS=PINETS_CLI_UNAVAILABLE|2788:TESTPINE_PREFLIGHT_STATUS=PINETS_CLI_UNAVAILABLE`
- `MASTER_UPDATED`: `NO`
- `PREFLIGHT_LINE`: `2725`
- `PROCESS_START`: `2611`
- `RETURNS_BEFORE_SOURCE`: `6`
- `SOURCE_PATH_FIRST`: `2715`
