# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-08-30T06:09:14.583654+00:00`
- Run ID: `20260830T060912Z`
- Step: `READ_EXISTING_CANDLE_LIST_SHAPE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXISTING_CANDLE_LIST_SHAPE_READ`
- Next gate: `USE_LIST_DIRECTLY_FOR_PINETS`

## Facts

- `APPEND_COUNT`: `1`
- `APPEND_EXPR`: `{&#x27;timestamp&#x27;: epoch, &#x27;time&#x27;: epoch, &#x27;open&#x27;: float(row[lower_map[&#x27;open&#x27;]]), &#x27;high&#x27;: float(row[lower_map[&#x27;high&#x27;]]), &#x27;low&#x27;: float(row[lower_map[&#x27;low&#x27;]]),`
- `CLOSE_KEY`: `YES`
- `CODE_CHANGED`: `NO`
- `DATE_KEY`: `NO`
- `DB_WRITE`: `NO`
- `ELEMENT_KEYS`: `timestamp,time,open,high,low,close,volume`
- `ELEMENT_KIND`: `DICT`
- `ERROR`: `NONE`
- `EXTEND_COUNT`: `0`
- `HIGH_KEY`: `YES`
- `LIST_ALREADY_PINETS_READY`: `YES`
- `LOW_KEY`: `YES`
- `MASTER_UPDATED`: `NO`
- `OPEN_KEY`: `YES`
- `TIMESTAMP_KEY`: `YES`
- `TIME_KEY`: `YES`
- `VOLUME_KEY`: `YES`
