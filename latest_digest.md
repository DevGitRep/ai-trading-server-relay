# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T14:47:19.164009+00:00`
- Run ID: `20260908T144717Z`
- Step: `READCHARTLOADBLOCK`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CHARTLOADBLOCKREAD`
- Next gate: `PATCHFREECHARTPROFILE`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `BLOCK1`: `TPL 752:{% set report_paid = tier in [&#x27;PRO&#x27;,&#x27;INTERNAL_ADMIN&#x27;] %} | 753:{% if benchtest_metrics or not report_paid %}`
- `BLOCK10`: `TPL 789:&lt;section class=&quot;benchtest-report-context irl-bench-compact&quot;&gt;`
- `BLOCK11`: `JS 1041:function irlReportNativeChartV28C(){ | 1042:if(!entitled){ | 1043:return;`
- `BLOCK12`: `JS 1044:} | 1046:const host=document.getElementById( | 1047:&quot;irlBenchChart&quot;`
- `BLOCK13`: `JS 1048:); | 1050:const stage=document.getElementById( | 1051:&quot;irlBenchChartStage&quot;`
- `BLOCK14`: `JS 1052:); | 1054:const meta=document.getElementById( | 1055:&quot;irlBenchChartMeta&quot;`
- `BLOCK15`: `JS 1056:); | 1058:if( | 1059:!host`
- `BLOCK16`: `JS 1060:||!stage | 1061:||host.dataset.chartState | 1062:){ | 1063:return;`
- `BLOCK17`: `JS 1064:} | 1066:host.dataset.chartState=&quot;waiting&quot;;`
- `BLOCK18`: `JS 1068:let started=false; | 1070:const start=async()=&gt;{ | 1071:if(started){`
- `BLOCK19`: `JS 1072:return; | 1073:} | 1075:started=true;`
- `BLOCK2`: `TPL 756:id=&quot;irlBenchChart&quot; | 757:class=&quot;irl-bench-chart-section irl-bench-chart-primary&quot; | 758:&gt; | 759:&lt;div class=&quot;i`
- `BLOCK20`: `JS 1076:host.dataset.chartState=&quot;loading&quot;; | 1078:const parts=location.pathname | 1079:.split(&quot;/&quot;)`
- `BLOCK21`: `JS 1080:.filter(Boolean); | 1082:const id=parts[ | 1083:parts.length-1`
- `BLOCK22`: `JS 1084:]; | 1086:if(!id || id===&quot;strategy&quot;){ | 1087:return;`
- `BLOCK23`: `JS 1088:} | 1090:const endpoint= | 1091:`/indicator-lab/strategy/${encodeURIComponent(`
- `BLOCK24`: `JS 1092:decodeURIComponent(id) | 1093:)}/bench-chart-data?view_as=${encodeURIComponent( | 1094:tier | 1095:)}`;`
- `BLOCK25`: `JS 1097:try{ | 1098:const response=await fetch( | 1099:endpoint,`
- `BLOCK26`: `JS 1100:{ | 1101:headers:{ | 1102:&quot;Accept&quot;:&quot;application/json&quot; | 1103:}`
- `BLOCK27`: `JS 1104:} | 1105:); | 1107:if(!response.ok){`
- `BLOCK28`: `JS 1108:throw new Error( | 1109:`chart ${response.status}` | 1110:); | 1111:}`
- `BLOCK3`: `TPL 761:&lt;h2&gt;Interactive BenchTest chart&lt;/h2&gt; | 763:&lt;div`
- `BLOCK4`: `TPL 764:id=&quot;irlBenchChartMeta&quot; | 765:class=&quot;irl-bench-chart-meta&quot; | 766:&gt; | 767:Actual tested data`
- `BLOCK5`: `TPL 768:&lt;/div&gt; | 770:&lt;/div&gt;`
- `BLOCK6`: `TPL 772:&lt;div | 773:id=&quot;irlBenchChartStage&quot; | 774:class=&quot;irl-bench-chart-stage&quot; | 775:&gt;`
- `BLOCK7`: `TPL 776:&lt;div class=&quot;irl-bench-chart-loading&quot;&gt; | 777:Interactive chart loads when visible | 778:&lt;/div&gt; | 779:&lt;/div&gt;`
- `BLOCK8`: `TPL 781:&lt;div class=&quot;irl-bench-chart-help&quot;&gt; | 782:Scroll to zoom drag to pan double-click to reset | 783:&lt;/div&gt;`
- `BLOCK9`: `TPL 784:&lt;/section&gt; | 787:&lt;div class=&quot;irl-bench-preview-row&quot;&gt;`
- `DB_WRITE`: `NO`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
