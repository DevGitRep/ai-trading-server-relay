# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-18T18:38:00.585328+00:00`
- Run ID: `20260918T183758Z`
- Step: `TRACEPRODUCTIONBINDING220`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `PRODUCTIONBINDINGLOCATED`
- Next gate: `TRACELOADTESTPINE`

## Facts

- `COMMIT`: `NO`
- `DB_WRITE`: `NO`
- `HEAD`: `398294cb1bc9`
- `PRODREF1`: `35:ASSIGN production : production or load_script(&#x27;testpine-preflight&#x27;)`
- `PRODREF2`: `36:ASSIGN tp : testpine or production.load_testpine()`
- `PRODREF3`: `253:ASSIGN production : load_script(&#x27;testpine-preflight&#x27;)`
- `PRODUCTION_REFS`: `5`
- `RAW1`: `28:def select_recent(count, production:None, testpine:None):`
- `RAW2`: `29:&quot;&quot;&quot;Reuse canonical corpus/order, independently of production result status.`
- `RAW3`: `35:production : production or load_script(&#x27;testpine-preflight&#x27;)`
- `RAW_LINES`: `8`
- `REPO_CLEAN`: `YES`
- `REPO_WRITE`: `NO`
- `RESTART`: `NO`
