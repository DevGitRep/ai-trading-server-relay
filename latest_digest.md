# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-18T03:28:40.875913+00:00`
- Run ID: `20260918T032838Z`
- Step: `MAPNATIVESTRATEGYCONTRACT113`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `NATIVESTRATEGYCONTRACTMAPPED`
- Next gate: `DESIGNONESHOTRESINPATCH`

## Facts

- `BENCH1`: `BENCH_FIELDS_ARTIFACT=strategy`
- `BENCH2`: `BENCH_FIELDS_OPEN_END=isOpen`
- `BENCH3`: `BENCH_FIELDS_ROW=profit,profitPercent,closeReason`
- `BENCH_VARS`: `4`
- `HEAD`: `d9df8c3c97ca`
- `IMPORT1`: `IMPORT:17:import { register } from &quot;node:module&quot;;`
- `IMPORT2`: `IMPORT:18:import { Console } from &quot;node:console&quot;;`
- `IMPORT_COUNT`: `5`
- `NATIVE_CALL`: `ACTIVE:271: const nativeRun = await run(`
- `PROD_DB_WRITE`: `NO`
- `REF_CAPTURED`: `603:nativeTradesCaptured:`
- `REF_EQ`: `286:const nativeEquitySeries = []; || 550:nativeEquitySeries.push( || 606:nativeEquitySeries,`
- `REF_OPEN`: `610:openPositionAtEnd: {`
- `REF_POS`: `287:const nativePositionSizeSeries = []; || 556:nativePositionSizeSeries.push( || 608:nativePositionSizeSeries,`
- `REF_TRADES`: `278:const nativeTrades = []; || 416:nativeTrades.push({ || 601:nativeTrades, || 603:nativeTradesCaptured: || 604:nativeTrades.length,`
- `REPO_CLEAN`: `YES`
- `REPO_WRITE`: `NO`
- `RESTART`: `NO`
- `SEARCH1`: `27`
- `SEARCH2`: `tools/resin_pine_adapter.mjs|295|closedTrades|closedTrades:`
- `SEARCH3`: `tools/resin_pine_adapter.mjs|297|closedTrades|s.closedTrades`
- `SEARCH_COUNT`: `27`
