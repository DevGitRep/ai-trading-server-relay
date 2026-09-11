# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T09:43:17.403685+00:00`
- Run ID: `20260911T094315Z`
- Step: `INSPECT_SHORT_REVIEW_CANDIDATE_ALIAS`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `REVIEW_CANDIDATE_KEY_AVAILABLE_FOR_CANONICAL_METRICS_MAP`
- Next gate: `PATCH_REVIEW_TO_REUSE_CANONICAL_METRICS_BY_CANDIDATE_ID`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CANONICAL_HELPER_IMPORTED`: `NO`
- `CANONICAL_METRIC_MAP_KEY`: `candidate_id`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `RESTART`: `NO`
- `REVIEW_CANDIDATE_SELECT`: `c.candidate_id,t.candidate_id,candidate_id,t.candidate_id`
- `REVIEW_CONN_NAMES`: `con`
- `REVIEW_MAIN_SELECT_COUNT`: `2`
- `REVIEW_ROW_ALREADY_USES_CANDIDATE_ID`: `NO`
- `REVIEW_ROW_KEYS`: `primary_max_drawdown_pct,primary_net_return_pct,primary_profit_factor,primary_trade_count,primary_win_rate_pct,secondary_win_rate_pct`
- `REVIEW_SELECT_HAS_CANDIDATE_ID`: `YES`
- `SOURCE_CHANGE`: `NO`
