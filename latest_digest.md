# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T15:41:31.829450+00:00`
- Run ID: `20260908T154129Z`
- Step: `READCHARTSTARTSIGNAL`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CHARTSTARTSIGNALREAD`
- Next gate: `PATCHFREECHARTSTART`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `DB_WRITE`: `NO`
- `HITS`: `14`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SIGNAL1`: `1058:!host | 1059:||!stage | 1060:||host.dataset.chartState | 1061:){ | 1062:return; | 1063:}`
- `SIGNAL10`: `2112:if( | 2113:entries.some( | 2114:entry=&gt;entry.isIntersecting | 2115:) | 2116:){ | 2117:observer.disconnect()`
- `SIGNAL11`: `2116:){ | 2117:observer.disconnect(); | 2118:start(); | 2119:} | 2120:}, | 2121:{`
- `SIGNAL12`: `2124:); | 2126:observer.observe( | 2127:host | 2128:);`
- `SIGNAL2`: `1063:} | 1065:host.dataset.chartState=&quot;waiting&quot;; | 1067:let started=false;`
- `SIGNAL3`: `1074:started=true; | 1075:host.dataset.chartState=&quot;loading&quot;; | 1077:const parts=location.pathname | 1078:.split(`
- `SIGNAL4`: `1194:+&#x27;&lt;/div&gt;&#x27;; | 1196:host.dataset.chartState=&quot;empty&quot;; | 1197:return; | 1198:}`
- `SIGNAL5`: `1198:} | 1200:host.dataset.chartState=&quot;ready&quot;; | 1202:meta.textContent=[ | 1203:payload.pair||&quot;&quot;,`
- `SIGNAL6`: `2075:new ResizeObserver( | 2076:render | 2077:).observe( | 2078:stage | 2079:);`
- `SIGNAL7`: `2098:+&#x27;&lt;/div&gt;&#x27;; | 2100:host.dataset.chartState= | 2101:&quot;error&quot;; | 2102:} | 2103:};`
- `SIGNAL8`: `2105:if( | 2106:&quot;IntersectionObserver&quot; | 2107:in window | 2108:){ | 2109:const observer=`
- `SIGNAL9`: `2108:){ | 2109:const observer= | 2110:new IntersectionObserver( | 2111:entries=&gt;{ | 2112:if( | 2113:entries.some`
- `SOURCE_CHANGE`: `NO`
