# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-18T03:30:52.637247+00:00`
- Run ID: `20260918T033050Z`
- Step: `EXACTPATCHFRAGMENTS115`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EXACTPATCHFRAGMENTSREADY`
- Next gate: `PATCHACTIVEADAPTER`

## Facts

- `ACTIVE1`: `ACTIVE:271: const nativeRun = await run( || ACTIVE:278: nativeRun?.viz || ACTIVE:282: const s = ctx.strategy; || ACTIVE:291: nativeRun?.plots || ACTIVE:294: strategy: { || ACTIVE:2`
- `ACTIVE2`: `95: closedTrades: || ACTIVE:297: s.closedTrades`
- `DECL`: `REF_DECL:278: const nativeTrades = []; || REF_DECL:286: const nativeEquitySeries = []; || REF_DECL:287: const nativePositionSizeSeries = [];`
- `HEAD`: `d9df8c3c97ca`
- `OUTPUT1`: `REF_OUTPUT:598: executionModel: || REF_OUTPUT:601: nativeTrades, || REF_OUTPUT:603: nativeTradesCaptured: || REF_OUTPUT:604: nativeTrades.length, || REF_OUTPUT:606: nativeEquitySer`
- `OUTPUT2`: `ies, || REF_OUTPUT:608: nativePositionSizeSeries, || REF_OUTPUT:610: openPositionAtEnd: {`
- `PROD_DB_WRITE`: `NO`
- `PROFIT`: `REF_TRADE:408: || !Number.isFinite(profit)`
- `REPO_CLEAN`: `YES`
- `REPO_WRITE`: `NO`
- `RESTART`: `NO`
- `SERIES1`: `REF_SERIES:544: const positionNow = || REF_SERIES:550: nativeEquitySeries.push( || REF_SERIES:551: Number.isFinite(equityNow) || REF_SERIES:552: ? equityNow || REF_SERIES:556: nati`
- `SERIES2`: `vePositionSizeSeries.push( || REF_SERIES:557: Number.isFinite(positionNow) || REF_SERIES:558: ? positionNow`
- `TRADE1`: `REF_TRADE:395: Number( REF_TRADE:396: nativeTradeValue( REF_TRADE:397: &quot;closedTradeProfitPercent&quot;, REF_TRADE:398: tradeNo, REF_TRADE:399: ) REF_TRADE:400: ); REF_TRADE:401: REF_TRA`
- `TRADE2`: `DE:402: if ( REF_TRADE:403: !Number.isFinite(size) REF_TRADE:404: || !Number.isFinite(entryPrice) REF_TRADE:405: || !Number.isFinite(exitPrice) REF_TRADE:406: || !Number.isFinite(e`
- `TRADE3`: `ntryBarIndex) REF_TRADE:407: || !Number.isFinite(exitBarIndex) REF_TRADE:408: || !Number.isFinite(profit) REF_TRADE:409: ) { REF_TRADE:410: throw new Error( REF_TRADE:411: &quot;NATIVE_`
