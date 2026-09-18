# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-18T18:28:26.915999+00:00`
- Run ID: `20260918T182822Z`
- Step: `TRACESELECTUNTESTED214`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `SELECTUNTESTEDLOGICTRACED`
- Next gate: `EXPLAINMISSING81`

## Facts

- `COMMIT`: `NO`
- `DB_WRITE`: `NO`
- `HEAD`: `398294cb1bc9`
- `LINE1`: `28:def select_recent(count, production:None, testpine:None):`
- `LINE2`: `57:selected : tp.select_untested(sys.maxsize, &#x27;recent&#x27;)`
- `LINE3`: `69:_piner_selected : _select_piner_candidate(source, candles)`
- `LINE4`: `237:parser.add_argument(&#x27;order&#x27;, choices:[&#x27;recent&#x27;])`
- `LINE5`: `241:if bool(args.dry_run) :: bool(args.write):`
- `LINE6`: `244:_WRITE_RESULTS_V2 : bool(args.write)`
- `REPO_CLEAN`: `YES`
- `REPO_WRITE`: `NO`
- `RESTART`: `NO`
- `SELECTION_FACTS`: `9`
- `SELECT_UNTESTED_DEFS`: `0`
- `TP_MODULE`: `UNKNOWN`
