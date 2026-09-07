# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-07T14:25:51.005546+00:00`
- Run ID: `20260907T142549Z`
- Step: `CAPTUREREALSORT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `REALISTICSORTMECHANISMSTILLPARTIAL`
- Next gate: `REVIEWCAPTUREDSEMANTICS`

## Facts

- `ANCESTOR1`: `rows.sort( key=lambda card: ( -_display_metric(card), _norm_title(card), ) )`
- `ANCESTOR2`: `NONE`
- `ANCESTORN`: `1`
- `BENCHTEST_RERUN`: `NO`
- `CHANGES_MADE`: `NO`
- `DB_WRITE`: `NO`
- `KEYEXPR`: `lambda card: ( -_display_metric(card), _norm_title(card), )`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `QUICK`: `ok`
- `RESTART`: `NO`
- `REVERSE`: `NONE`
- `SCORED`: `16`
- `SEM1`: `def _indicator_lab_library_page_v26( cards, tier, q=&quot;&quot;, sort_key=&quot;realistic&quot;, page=1, page_size=12, ): tier =`
- `SEM1LINE`: `582`
- `SEM2`: `metric_fields = { &quot;realistic&quot;: &quot;realistic_score&quot;, &quot;profit&quot;: &quot;profit_factor&quot;, &quot;return&quot;: &quot;net_return_pct&quot;, &quot;win&quot;`
- `SEM2LINE`: `623`
- `SEM3`: `sort_key = ( sort_key if sort_key in metric_fields else &quot;realistic&quot; )`
- `SEM3LINE`: `634`
- `SEM4`: `field = metric_fields[ sort_key ]`
- `SEM4LINE`: `641`
- `SEM5`: `def _display_metric(card): if not entitled: return float(&quot;-inf&quot;)  BENCH_SCORE_V2_REALISTIC_TOPLEVEL_SORT_V31AB`
- `SEM5LINE`: `645`
- `SEMN`: `7`
- `SORTCALL`: `rows.sort( key=lambda card: ( -_display_metric(card), _norm_title(card), ) )`
- `SORTLINE`: `680`
- `SORTOWNER`: `rows`
- `SORTTYPE`: `METHOD`
- `SOURCE_CHANGE`: `NO`
