# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-18T03:37:09.283037+00:00`
- Run ID: `20260918T033707Z`
- Step: `READEXACTNATIVECAPTURESCOPES121`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `NATIVECAPTURESCOPESREAD`
- Next gate: `PATCHACTIVEADAPTERV2`

## Facts

- `ACTIVE`: `const result = await run( | const nativeRun = await run( | const s = ctx.strategy; | strategy: { | closedTrades: | s.closedTrades`
- `DECL1`: `const nativeTrades = []; | const nativeEquitySeries = []; | const nativePositionSizeSeries = []; | let capturedClosedTrades = 0; | function nativeTradeValue( | !== &quot;function&quot; | fun`
- `DECL2`: `ction captureNativeClosedTrades() {`
- `HEAD`: `d9df8c3c97ca`
- `OUTPUT1`: `executionModel: | nativeTrades, | nativeTradesCaptured: | nativeTrades.length, | nativeEquitySeries, | nativePositionSizeSeries, | openPositionAtEnd: {`
- `OUTPUT2`: ``
- `PROD_DB_WRITE`: `NO`
- `REPO_CLEAN`: `YES`
- `REPO_WRITE`: `NO`
- `RESTART`: `NO`
- `SERIES1`: `* Resin 0.2.2 exposes strategy.equity as: | * strategy.equity(closePrice) | const equityNow = | typeof strategyState.equity | strategyState.equity( | const positionNow = | strategy`
- `SERIES2`: `State.posSize | nativeEquitySeries.push( | Number.isFinite(equityNow) | ? equityNow | nativePositionSizeSeries.push( | Number.isFinite(positionNow) | ? positionNow`
- `TRADE1`: `strategyState.closedTrades | &lt; capturedClosedTrades | capturedClosedTrades | capturedClosedTrades; | nativeTradeValue( | const entryPrice = | nativeTradeValue( | const exitPrice =`
- `TRADE2`: `| nativeTradeValue( | const entryBarIndex = | nativeTradeValue( | const exitBarIndex = | nativeTradeValue( | const profit = | nativeTradeValue( | const profitPercent = | nativeTrad`
- `TRADE3`: `eValue( | || !Number.isFinite(entryPrice) | || !Number.isFinite(exitPrice) | || !Number.isFinite(entryBarIndex) | || !Number.isFinite(exitBarIndex) | || !Number.isFinite(profit) |`
