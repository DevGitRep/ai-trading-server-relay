# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T11:02:01.149501+00:00`
- Run ID: `20260908T110159Z`
- Step: `READCARDSORTEXACT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CARDSORTEXACTREAD`
- Next gate: `PATCHLIBRARYCARDS`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `BULK1`: `metrics_map = {}`
- `BULK2`: `SELECT`
- `BULK3`: `indicator_id,`
- `BULK4`: `FROM indicator_pipeline_current`
- `BULK5`: `candidate_id = str(row[&quot;indicator_id&quot;])`
- `CALL1`: `NONE`
- `CALL2`: `NONE`
- `CALL3`: `NONE`
- `CALL4`: `NONE`
- `DB_WRITE`: `NO`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `OWNER1`: `_card_sort_key:def _card_sort_key(card):`
- `OWNER2`: `_card_sort_key:&quot;realistic_score&quot;`
- `OWNER3`: `_card_sort_key:net_return = metrics.get(`
- `OWNER4`: `_card_sort_key:&quot;net_return_pct&quot;`
- `OWNER5`: `_card_sort_key:return (`
- `OWNER6`: `_card_sort_key:net_return`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SORT1`: `def _card_sort_key(card): | metrics = card[&quot;metrics&quot;]`
- `SORT2`: `score = metrics.get( | &quot;realistic_score&quot;`
- `SORT3`: `) | net_return = metrics.get(`
- `SORT4`: `&quot;net_return_pct&quot; | )`
- `SORT5`: `return ( | 1 if score is not None else 0,`
- `SORT6`: `( | score`
- `SORT7`: `if score is not None | else float(&quot;-inf&quot;)`
- `SORT8`: `), | (`
- `SOURCE_CHANGE`: `NO`
