# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T14:32:29.730651+00:00`
- Run ID: `20260908T143227Z`
- Step: `READFREEPROFILEKEYS`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `FREEPROFILEKEYSREAD`
- Next gate: `PATCHFREECHARTPROFILE`

## Facts

- `ACTIVITY_KEYS`: `primary_exposure_pct,trade_count`
- `BENCHTEST_RERUN`: `NO`
- `DB_WRITE`: `NO`
- `DIRECTION_KEYS`: `direction_left_count,direction_left_label,direction_left_pct,direction_right_count,direction_right_label,direction_r`
- `DNA_KEYS`: `direction_mode`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `ROUTE1`: `2370:_indicator_lab_internal_request_authorized() | 2371:) | 2373:requested_tier = str( | 2374:_indicator_lab_requeste`
- `ROUTE2`: `2380:and requested_tier | 2381:in { | 2382:&#x27;FREE&#x27;, | 2383:&#x27;PRO&#x27;, | 2384:&#x27;INTERNAL_ADMIN&#x27;,`
- `ROUTE3`: `2385:} | 2386:): | 2387:effective_tier = requested_tier | 2388:else: | 2389:effective_tier = &#x27;FREE&#x27;`
- `ROUTE4`: `2391:benchtest_metrics = ( | 2392:_pine_report_metrics( | 2393:candidate_id, | 2394:effective_tier,`
- `ROUTE5`: `2395:) | 2396:) | 2398:return render_template( | 2399:&#x27;indicator_lab_report.html&#x27;,`
- `ROUTE6`: `2400:record=record, | 2401:source_meta=source_meta, | 2402:benchtest_metrics=benchtest_metrics, | 2403:tier=effective_`
- `ROUTE7`: `NONE`
- `ROUTE8`: `NONE`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
- `TAG_KEYS`: `profile_tags`
