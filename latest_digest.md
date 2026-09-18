# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-18T18:27:12.880127+00:00`
- Run ID: `20260918T182710Z`
- Step: `INSPECTPREFLIGHTSELECTION213`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `PREFLIGHTRECENTLOGICLOCATED`
- Next gate: `EXPLAINWHY81NOTSELECTED`

## Facts

- `COMMIT`: `NO`
- `DB_WRITE`: `NO`
- `ORCHESTRATOR`: `tools/atb_preflight_v2/orchestrator.py`
- `PACKAGE_FILES`: `12`
- `RECENT1`: `orchestrator.py:57:selected : tp.select_untested(sys.maxsize, &#x27;recent&#x27;)`
- `RECENT2`: `orchestrator.py:237:parser.add_argument(&#x27;order&#x27;, choices:[&#x27;recent&#x27;])`
- `RECENT3`: `orchestrator.py:248:# unrelated recent candidates if a production TYS selector is inherited.`
- `RECENT4`: `NONE`
- `RECENT_HITS`: `3`
- `REPO_CLEAN`: `YES`
- `REPO_WRITE`: `NO`
- `RESTART`: `NO`
- `SELECTION_HITS`: `83`
