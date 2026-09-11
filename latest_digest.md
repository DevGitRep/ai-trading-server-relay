# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T09:20:47.417400+00:00`
- Run ID: `20260911T092045Z`
- Step: `MAP_CANONICAL_METRIC_HELPER_REUSE_POINT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CANONICAL_METRIC_HELPER_REUSE_POINT_RESOLVED`
- Next gate: `PATCH_REVIEW_TO_CALL_EXISTING_BULK_PIPELINE_METRICS_HELPER`

## Facts

- `ASSIGN1`: `151:rows_=_con.execute(__SELECT_t.submission_id,_t.created_epoch_ms,_t.email,_t.technical_status,_t.benchtest_status,_c.name,_c.source_author,_COALESCE(_p.library_publication_status,_t.library_publication_status_)_`
- `ASSIGN2`: `47:submission_id_=_str(_request.form.get(_submission_id,_,_)_).strip()`
- `ASSIGN3`: `61:row_=_con.execute(__SELECT_submission_id,_candidate_id,_source_sha256,_library_review_allowed,_technical_status,_benchtest_status_FROM_test_your_script_submissions_v1_WHERE_submission_id=_LIMIT_1_,_(submission_`
- `BENCHTEST_RUN`: `NO`
- `CANONICAL_USES_RAW_RESULT`: `YES`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `LOOP1`: `249:for_r_in_rows:_view.append({_id:_r[submission_id],_date:_fmt_dt(_r[created_epoch_ms]_),_name:_r[name]_or_-,_email:_r[email]_or_-,_author:_r[source_author]_or_-,_pf:_fmt(_r[primary_profit_factor]_),_trades:_(_st`
- `METRIC_HELPER_ARGS`: `conn`
- `METRIC_HELPER_KEYS`: `max_drawdown_pct,net_return_pct,primary_max_drawdown_pct,primary_net_return_pct,primary_profit_factor,primary_trade_count,primary_win_rate_pct,profit_factor,secondary_win_rate_pct,trade_count,win_rate_pct`
- `METRIC_HELPER_RETURNS_MAP_LIKE`: `NO`
- `METRIC_HELPER_RETURN_COUNT`: `6`
- `RESTART`: `NO`
- `RETURN1`: `metrics_map`
- `RETURN2`: `round(_max(_0.0,_min(_100.0,_(_(_float(_value)_+_2.0_)__4.0_)__100.0,_),_),_1,_)`
- `RETURN3`: `None`
- `RETURN4`: `float(__value_)`
- `REVIEW_ASSIGNMENT_COUNT`: `3`
- `REVIEW_CHAIN_ALREADY_PRESENT`: `YES`
- `REVIEW_LOOP_COUNT`: `1`
- `REVIEW_USES_RAW_RESULT`: `NO`
- `SOURCE_CHANGE`: `NO`
