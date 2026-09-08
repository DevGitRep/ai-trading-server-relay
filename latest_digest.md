# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T14:44:27.825101+00:00`
- Run ID: `20260908T144425Z`
- Step: `READCHARTENDPOINT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CHARTENDPOINTREAD`
- Next gate: `PATCHFREECHARTPROFILE`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `CODE1`: `TPL 750:&lt;!-- REPORT_CHART_FIRST_COMPACT_BENCH_V28G2 --&gt; | 752:{% set report_paid = tier in [&#x27;PRO&#x27;,&#x27;INTERNAL_ADMIN&#x27;] %} |`
- `CODE10`: `TPL 795:&lt;div class=&quot;benchtest-context-item&quot;&gt; | 796:&lt;span&gt;Realistic Score&lt;/span&gt; | 797:&lt;strong&gt;`
- `CODE11`: `TPL 798:{% if report_paid %}{{ (&#x27;%.1f&#x27;|format(benchtest_metrics.get(&#x27;realistic_score&#x27;))) ~ &#x27; / 100&#x27; if benchtest_metrics`
- `CODE12`: `TPL 802:&lt;div class=&quot;benchtest-context-item&quot;&gt; | 803:&lt;span&gt;Profit Factor&lt;/span&gt; | 804:&lt;strong&gt; | 805:{% if report_paid %}{`
- `CODE13`: `TPL 806:&lt;/strong&gt; | 807:&lt;/div&gt; | 809:&lt;div class=&quot;benchtest-context-item&quot;&gt;`
- `CODE14`: `TPL 810:&lt;span&gt;Net Return&lt;/span&gt; | 811:&lt;strong&gt; | 812:{% if benchtest_metrics.score_cohort_size is not none %} | 813:{% i`
- `CODE15`: `TPL 818:&lt;/div&gt; | 820:&lt;div class=&quot;benchtest-context-item&quot;&gt; | 821:&lt;span&gt;Max Drawdown&lt;/span&gt;`
- `CODE16`: `TPL 822:&lt;strong&gt; | 823:{% if report_paid %}{{ (&#x27;%.2f&#x27;|format(benchtest_metrics.get(&#x27;max_drawdown_pct&#x27;))) ~ &#x27;%&#x27; if bencht`
- `CODE17`: `TPL 826:&lt;!-- BENCHTEST_V2_PRIMARY_METRICS --&gt; | 827:&lt;div class=&quot;benchtest-context-item&quot;&gt; | 828:&lt;span&gt;Win Rate&lt;/span&gt; | 8`
- `CODE18`: `TPL 830:{% if report_paid %}{{ (&#x27;%.2f&#x27;|format(benchtest_metrics.get(&#x27;win_rate_pct&#x27;))) ~ &#x27;%&#x27; if benchtest_metrics.get(&#x27;wi`
- `CODE19`: `TPL 834:&lt;span&gt;Trades&lt;/span&gt; | 835:&lt;strong&gt; | 836:{% if report_paid %}{{ benchtest_metrics.get(&#x27;trade_count&#x27;) if benchtes`
- `CODE2`: `TPL 755:&lt;section | 756:id=&quot;irlBenchChart&quot; | 757:class=&quot;irl-bench-chart-section irl-bench-chart-primary&quot;`
- `CODE20`: `TPL 842:&lt;div class=&quot;benchtest-score-note&quot;&gt; | 843:&lt;strong&gt;Realistic Score&lt;/strong&gt; | 844:is a relative ranking within the`
- `CODE21`: `TPL 852:{% if record.get(&quot;image_url&quot;) %}`
- `CODE22`: `TPL 858:src=&quot;{{ record.get(&quot;image_url&quot;) }}&quot; | 859:alt=&quot;{{ record.get(&#x27;name&#x27;) or record.get(&#x27;script_name&#x27;) or &#x27;Indicator`
- `CODE23`: `TPL 870:{% else %} | 872:{% if record.get(&quot;image_url&quot;) %}`
- `CODE24`: `TPL 878:src=&quot;{{ record.get(&quot;image_url&quot;) }}&quot; | 879:alt=&quot;{{ record.get(&#x27;name&#x27;) or record.get(&#x27;script_name&#x27;) or &#x27;Indicator`
- `CODE3`: `TPL 758:&gt; | 759:&lt;div class=&quot;irl-bench-chart-head&quot;&gt; | 761:&lt;h2&gt;Interactive BenchTest chart&lt;/h2&gt;`
- `CODE4`: `TPL 763:&lt;div | 764:id=&quot;irlBenchChartMeta&quot; | 765:class=&quot;irl-bench-chart-meta&quot;`
- `CODE5`: `TPL 770:&lt;/div&gt; | 772:&lt;div | 773:id=&quot;irlBenchChartStage&quot;`
- `CODE6`: `TPL 774:class=&quot;irl-bench-chart-stage&quot; | 775:&gt; | 776:&lt;div class=&quot;irl-bench-chart-loading&quot;&gt; | 777:Interactive chart loads`
- `CODE7`: `TPL 778:&lt;/div&gt; | 779:&lt;/div&gt; | 781:&lt;div class=&quot;irl-bench-chart-help&quot;&gt;`
- `CODE8`: `TPL 787:&lt;div class=&quot;irl-bench-preview-row&quot;&gt; | 789:&lt;section class=&quot;benchtest-report-context irl-bench-compact&quot;&gt;`
- `CODE9`: `TPL 791:&lt;h2&gt;12-month BenchTest&lt;/h2&gt; | 793:&lt;div class=&quot;benchtest-context-grid&quot;&gt;`
- `DB_WRITE`: `NO`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
