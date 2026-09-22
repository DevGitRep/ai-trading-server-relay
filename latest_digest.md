# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-22T07:56:29.514423+00:00`
- Run ID: `20260922T075627Z`
- Step: `CASE4S3INSPECT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CASE4_S3_IMPLEMENTATION_INSPECTED`
- Next gate: `DIAGNOSE_CASE4_S3_SEMANTIC_DIFFERENCE`

## Facts

- `DASHBOARD_RESTART`: `NO`
- `F1`: `CSHARP S3 REFERENCES`
- `F10`: `184: &quot;expr&quot;: &quot;sma20 &gt; sma20[1]&quot;`
- `F11`: `187: &quot;name&quot;: &quot;sma20Down&quot;,`
- `F12`: `189: &quot;expr&quot;: &quot;sma20 &lt; sma20[1]&quot;`
- `F13`: `192: &quot;name&quot;: &quot;sma20DownCount&quot;,`
- `F14`: `194: &quot;expr&quot;: &quot;sma20DownCount + 1&quot;`
- `F15`: `197: &quot;name&quot;: &quot;sma20UpCount&quot;,`
- `F16`: `202: &quot;name&quot;: &quot;sma20Intensity&quot;,`
- `F17`: `204: &quot;expr&quot;: &quot;sma20Up ? math.min(100, (sma20UpCount / intensityBars) * 100) : sma20Down ? math.min(100, (sma20DownCount / intensityBars) * 100) : 0&quot;`
- `F18`: `207: &quot;name&quot;: &quot;sma20Color&quot;,`
- `F19`: `209: &quot;expr&quot;: &quot;sma20Up ? color.new(colSMA20Up, 90 - (sma20Intensity * 0.7)) : sma20Down ? color.new(colSMA20Down, 90 - (sma20Intensity * 0.7)) : color.gray&quot;`
- `F2`: `RUNTIME SPEC S3`
- `F20`: `234: &quot;expr&quot;: &quot;rsiUp ? math.min(100, (rsiUpCount / intensityBars) * 100) : rsiDown ? math.min(100, (rsiDownCount / intensityBars) * 100) : 0&quot;`
- `F21`: `244: &quot;expr&quot;: &quot;close &gt; sma20 and sma20 &gt; vwap and ema8 &gt; ema21 and sma20 &gt; sma20[1]&quot;`
- `F22`: `249: &quot;expr&quot;: &quot;close &lt; sma20 and sma20 &lt; vwap and ema8 &lt; ema21 and sma20 &lt; sma20[1]&quot;`
- `F23`: `278: &quot;expr&quot;: &quot;sma20Color&quot;`
- `F24`: `PINE S3 REFERENCES`
- `F3`: `17: &quot;name&quot;: &quot;intensityBars&quot;,`
- `F4`: `53: &quot;name&quot;: &quot;colSMA20Up&quot;,`
- `F5`: `59: &quot;name&quot;: &quot;colSMA20Down&quot;,`
- `F6`: `97: &quot;name&quot;: &quot;sma20&quot;,`
- `F7`: `144: &quot;expr&quot;: &quot;ema8Up ? math.min(100, (ema8UpCount / intensityBars) * 100) : ema8Down ? math.min(100, (ema8DownCount / intensityBars) * 100) : 0&quot;`
- `F8`: `174: &quot;expr&quot;: &quot;ema21Up ? math.min(100, (ema21UpCount / intensityBars) * 100) : ema21Down ? math.min(100, (ema21DownCount / intensityBars) * 100) : 0&quot;`
- `F9`: `182: &quot;name&quot;: &quot;sma20Up&quot;,`
- `HEAD`: `939755327f6d`
- `PRODUCTION_CODE_WRITES`: `0`
- `PRODUCTION_DB_WRITES`: `0`
- `REPO_CLEAN`: `YES`
