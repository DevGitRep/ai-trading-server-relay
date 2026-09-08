# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T07:51:15.896589+00:00`
- Run ID: `20260908T075113Z`
- Step: `READCHARTTEMPLATE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CHARTTEMPLATECONTRACTREAD`
- Next gate: `PATCHCANONICALREPORTUI`

## Facts

- `ABSUSE`: `em&quot;&gt; &lt;span&gt;Absolute status&lt;/span&gt; &lt;strong&gt; {{ benchtest_metrics.absolute_profitability_status |replace(&#x27;_&#x27;, &#x27; &#x27;) |title }} &lt;/strong&gt; &lt;/div&gt;`
- `BENCHTEST_RERUN`: `NO`
- `CHART_CANVAS`: `NO`
- `CHART_FIELDS`: `test_status,absolute_profitability_status,score_cohort_size,signal_role`
- `CHART_JS`: `NO`
- `COHORTUSE`: `em&quot;&gt; &lt;span&gt;Score cohort&lt;/span&gt; &lt;strong&gt; {% if benchtest_metrics.score_cohort_size is not none %} {{ benchtest_metrics.score_cohort_size }} {`
- `DB_WRITE`: `NO`
- `DDUSE`: `NONE`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `OLD_ABS`: `ABSENT`
- `OLD_COHORT`: `ABSENT`
- `OLD_ROLE`: `ABSENT`
- `OLD_TEST`: `ABSENT`
- `PFUSE`: `NONE`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `RETURNUSE`: `NONE`
- `ROLEUSE`: `&lt;span&gt;Signal classification&lt;/span&gt; &lt;strong&gt; {{ (benchtest_metrics.signal_role or &#x27;Not classified&#x27;) |replace(&#x27;_&#x27;, &#x27; &#x27;) |title }} &lt;/strong&gt; &lt;/`
- `SCOREUSE`: `NONE`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
- `TESTUSE`: `t-item&quot;&gt; &lt;span&gt;Test status&lt;/span&gt; &lt;strong&gt; {{ benchtest_metrics.test_status or &#x27;Not BenchTested&#x27; }} &lt;/strong&gt; &lt;/div&gt; &lt;div class=&quot;benchtest-c`
- `TRADEUSE`: `NONE`
- `WINUSE`: `NONE`
