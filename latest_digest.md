# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-08-30T05:31:09.892967+00:00`
- Run ID: `20260830T053107Z`
- Step: `READ_TESTPINE_ITEM_PRODUCER`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `TESTPINE_ITEM_PRODUCER_READ`
- Next gate: `APPLY_DOCUMENTED_STORED_SOURCE_BINDING`

## Facts

- `CALL_LINE`: `3397`
- `CODE_CHANGED`: `NO`
- `DB_WRITE`: `NO`
- `ENCLOSING_FOR`: `YES`
- `ERROR`: `NONE`
- `FOR_ITER`: `enumerate(_tp_items, start=1)`
- `FOR_LINE`: `3391`
- `FOR_TARGET`: `(_tp_seq, _tp_item)`
- `ITEM_GET_KEYS`: `query`
- `ITEM_WRITE_KEYS`: `_testpine_documented_pinets_preflight_v1`
- `ITER_SOURCE`: `_tp_items=_tp_json.load(_tp_fh)`
- `ITER_SOURCE_LINE`: `3388`
- `MASTER_UPDATED`: `NO`
- `QUERY_EXPR`: `_tp_item.get(&#x27;query&#x27;) or &#x27;PINE_LIBRARY&#x27;`
