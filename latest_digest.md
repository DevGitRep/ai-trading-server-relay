# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-10T14:19:00.643581+00:00`
- Run ID: `20260910T141858Z`
- Step: `IDENTIFY_EXACT_VERSION1_WORKER_REGRESSION`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `VERSION1_EXACT_NON_SELECTOR_DIFF_FOUND`
- Next gate: `RESTORE_VERSION1_PROVEN_CODE_DIFFERENCE`

## Facts

- `ADDED_LINES`: `1`
- `BENCHTEST_RUN`: `NO`
- `CANDIDATE_SELECTOR_RESTORE`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `CURRENT_HASH`: `e1814ff78210fb0e`
- `CURRENT_STATEMENTS`: `36`
- `DB_WRITE`: `NO`
- `FEATURE_CHANGES`: `NONE`
- `NEW_1`: `proc = subprocess.run([&#x27;&lt;PATH&gt;&#x27;, &#x27;1&#x27;, &#x27;recent&#x27;], cwd=str(ROOT), stdout=subprocess.PIPE, stderr=subprocess.STDOUT, text=True)`
- `OLD_1`: `proc = subprocess.run([&#x27;&lt;PATH&gt;&#x27;, &#x27;&lt;SELECTOR&gt;&#x27;, candidate_id], cwd=str(ROOT), stdout=subprocess.PIPE, stderr=subprocess.STDOUT, text=True)`
- `OLD_STATEMENTS`: `36`
- `REMOVED_LINES`: `1`
- `RESTART`: `NO`
- `SELECTOR_DIFFERENCE_IGNORED`: `YES`
- `SOURCE_CHANGE`: `NO`
- `TARGET_SELECTOR`: `BENCHTEST_1_RECENT`
- `VERSION1_HASH`: `ef08f10030895d53`
- `VERSION1_TIMESTAMP`: `2026-09-10T13:02:12.345065+00:00`
