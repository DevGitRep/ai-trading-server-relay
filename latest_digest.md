# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-18T03:13:26.584115+00:00`
- Run ID: `20260918T031324Z`
- Step: `READNATIVETRADELEDGERCONTRACT102`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `NATIVETRADELEDGERCONTRACTREAD`
- Next gate: `PATCHSTRATEGYTRADELEDGER`

## Facts

- `HEAD`: `d9df8c3c97ca`
- `HITS`: `20`
- `L1`: `=== _v2_native_strategy ledger block 3158-3235 ===`
- `L10`: `3186 native_trades`
- `L2`: `3161 raise RuntimeError(`
- `L3`: `3162 &quot;V2_NATIVE_STRATEGY_MODEL_INVALID:&quot;`
- `L4`: `3166 native_trades=strategy.get(`
- `L5`: `3167 &quot;nativeTrades&quot;`
- `L6`: `3171 native_trades,`
- `L7`: `3174 raise RuntimeError(`
- `L8`: `3175 &quot;V2_NATIVE_TRADE_LEDGER_MISSING&quot;`
- `L9`: `3180 &quot;nativeTradesCaptured&quot;`
- `PROD_DB_WRITE`: `NO`
- `REPO_CLEAN`: `YES`
- `REPO_WRITE`: `NO`
- `RESTART`: `NO`
