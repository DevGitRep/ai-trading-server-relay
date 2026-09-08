# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T11:12:02.671337+00:00`
- Run ID: `20260908T111200Z`
- Step: `READLIBFETCHSORT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `LIBFETCHSORTREAD`
- Next gate: `PATCHLIBRARYCARDS`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `CTX1`: `842:const sort=document.getElementById( | &quot;irlSort&quot; | ); | const url=new URL( | &quot;/indicator-lab/api/library-page&quot;,`
- `CTX2`: `888:try{ | const response=await fetch( | url.toString(), | { | headers:{ | &quot;Accept&quot;:`
- `CTX3`: `948:document.getElementById( | &quot;irlSort&quot; | ).addEventListener( | &quot;change&quot;, | ()=&gt;{ | loadPage(`
- `CTX4`: `999:if(entitled){ | fetch( | `/indicator-lab/api/library-stats?view_as=${encodeURIComponent(tier)}` | ) | .then(r=&gt;`
- `CTX5`: `1098:try{ | const response=await fetch( | endpoint, | { | headers:{ | &quot;Accept&quot;:&quot;application/json&quot;`
- `CTX6`: `2678:const sort = | document.getElementById(&quot;irlSort&quot;); | if (sort) { | const field = | sort.closest(&quot;.irl-v2-field`
- `DB_WRITE`: `NO`
- `HIT1`: `64:* PRO/INTERNAL cards already contain projected`
- `HIT10`: `314:key===&quot;net_return_pct&quot;`
- `HIT2`: `65:* BenchTest metrics. FREE cards explicitly do not.`
- `HIT3`: `67:const cards=Array.from(`
- `HIT4`: `72:cards.some(card=&gt;{`
- `HIT5`: `108:shell.innerHTML=`&lt;div class=&quot;irl-v2-stats&quot;&gt;&lt;div class=&quot;irl-v2-stat&quot;&gt;&lt;div class=&quot;irl-v2-label&quot;&gt;Indicat`
- `HIT6`: `287:[&quot;Profit Factor&quot;,&quot;profit_factor&quot;],`
- `HIT7`: `288:[&quot;Net Return&quot;,&quot;net_return_pct&quot;],`
- `HIT8`: `290:[&quot;Win Rate&quot;,&quot;win_rate_pct&quot;],`
- `HIT9`: `292:[&quot;Realistic Score&quot;,&quot;realistic_score&quot;]`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
