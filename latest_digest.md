# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-21T22:09:26.861858+00:00`
- Run ID: `20260921T220921Z`
- Step: `CASE4TRANSITIONS`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CASE4_COLOR_STATE_TRANSITIONS_RECOVERED`
- Next gate: `IMPLEMENT_CASE4_INDEPENDENT_LEAN_SIGNAL_PORT`

## Facts

- `COLOR0`: `ema8Color:ema8Up ? color.new(colEMA8Up, 90 - (ema8Intensity * 0.7)) : ema8Down ? color.new(c`
- `COLOR1`: `ema21Color:ema21Up ? color.new(colEMA21Up, 90 - (ema21Intensity * 0.7)) : ema21Down ? color.`
- `COLOR2`: `sma20Color:sma20Up ? color.new(colSMA20Up, 90 - (sma20Intensity * 0.7)) : sma20Down ? color.`
- `COLOR3`: `NONE`
- `COLOR4`: `showBackground ? color.new(bgCol, 93) : na`
- `COLOR5`: `showRSIpane and rsi &gt; 70 ? color.new(color.red, 95) : showRSIpane and rsi &lt; 30 ? color.new(c`
- `DASHBOARD_RESTART`: `NO`
- `HEAD`: `939755327f6d`
- `LONG_TRANSITION`: `RED_TO_GREEN`
- `PRODUCTION_CODE_WRITES`: `0`
- `PRODUCTION_DB_WRITES`: `0`
- `REPO_CLEAN`: `YES`
- `SHORT_TRANSITION`: `GREEN_TO_RED`
- `SOURCE_COUNT`: `6`
- `TRANSITION_RULE`: `LONG:RED_TO_GREEN;SHORT:GREEN_TO_RED`
