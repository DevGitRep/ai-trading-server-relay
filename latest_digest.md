# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-17T09:14:29.390906+00:00`
- Run ID: `20260917T091427Z`
- Step: `TRACE_EVENT_ADAPTER_INPUT_CONTRACT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EVENT_ADAPTER_INPUT_CONTRACT_RESOLVED`
- Next gate: `CONVERT_SELECTED_EXPRESSION_EVENTS_TO_EXISTING_ADAPTER_SCHEMA_AND_RUN_QUANT`

## Facts

- `ACCEPTED_SCHEMA`: `SEE_FACTS`
- `ATB_CHANGED`: `NO`
- `DASHBOARD_RESTART`: `NO`
- `DB_WRITES`: `0`
- `EVENT_ACCESS`: `L215:events.get(_events_),L198:events[key],L208:events[key]`
- `EVENT_BRANCHES`: `L189:isinstance(_events,_dict,_),L219:isinstance(_event_list,_(list,_tuple),_),L268:isinstance(_events,_(list,`
- `FAILURE`: `NONE`
- `INTERNAL_RC`: `0`
- `NORMALIZED_OUTPUT`: `L328:{_signal_bars:_[_row[0]_for_row_in_rows_],_signal_dirs:_[_row[1]_for_row_in_rows_],_}`
- `READ_ONLY`: `YES`
- `REGRESSION_CALLS`: `L67:provider_events_to_contract(_case[events],_case[_candle_count_],_)`
- `REGRESSION_EVENT_FIXTURES`: `L66:provider_events_to_contract(_case[events],_case[_candle_count_],_)`
- `SIGNATURE`: `provider_events_to_contract(events,candle_count)`
