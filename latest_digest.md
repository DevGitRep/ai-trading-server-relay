# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-10-01T11:18:54.485665+00:00`
- Run ID: `20261001T111852Z`
- Step: `BENCHTEST_TRADE_MINIMUM_STORAGE_AUDIT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `MINIMUM_STORAGE_INPUT_READY`
- Next gate: `DESIGN_COMPACT_CHART_STORAGE`

## Facts

- `CALLERS`: ``
- `DB_READS`: `0`
- `DB_WRITES`: `0`
- `DELETIONS`: `0`
- `FILE_WRITES`: `0`
- `FILTERS`: `register_indicator_lab_routes=run_id=? AND candidate_id=?;indicator_lab_report_bench_chart_data_v28c=run_id=? AND candidate_id=?`
- `RAW_JSON`: `register_indicator_lab_routes=Y;indicator_lab_report_bench_chart_data_v28c=Y`
- `READERS`: `indicator_lab_v1.py:register_indicator_lab_routes;indicator_lab_v1.py:indicator_lab_report_bench_chart_data_v28c`
- `SELECTED_COLUMNS`: `register_indicator_lab_routes=raw_json;indicator_lab_report_bench_chart_data_v28c=raw_json`
