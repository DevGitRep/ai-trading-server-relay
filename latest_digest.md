# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-18T18:33:11.708572+00:00`
- Run ID: `20260918T183307Z`
- Step: `STATICTRACESELECTUNTESTED216`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `TPANDSELECTUNTESTEDSTATICALLYTRACED`
- Next gate: `EXPLAINWHY81NOTSELECTED`

## Facts

- `BINDING1`: `36:ASSIGN tp=testpine or production.load_testpine()`
- `BINDING2`: `NONE`
- `COMMIT`: `NO`
- `DB_WRITE`: `NO`
- `HEAD`: `398294cb1bc9`
- `REPO_CLEAN`: `YES`
- `REPO_WRITE`: `NO`
- `RESTART`: `NO`
- `TP_BINDINGS`: `1`
- `UNT1`: `test_atb_preflight_v2.py:332:tp.select_untested : writer`
- `UNT2`: `orchestrator.py:57:selected : tp.select_untested(sys.maxsize, &#x27;recent&#x27;)`
- `UNT3`: `NONE`
- `UNT4`: `NONE`
- `UNTESTED_HITS`: `2`
