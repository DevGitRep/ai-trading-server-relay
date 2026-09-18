# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-18T03:43:49.686737+00:00`
- Run ID: `20260918T034347Z`
- Step: `COMPAREFULLADAPTERSNATIVEDIFF127`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `REALNATIVEDIFFMAPPED`
- Next gate: `PATCHREALNATIVEBLOCKS`

## Facts

- `FULL_DIFF_BLOCKS`: `14`
- `HEAD`: `d9df8c3c97ca`
- `N1`: `BLOCK:8|insert|A:258-257|R:266-495`
- `N1_REF`: `/* | * BENCHTEST_V2_NATIVE_STRATEGY_LEDGER_V30K | * | * Capture Resin-native closed trades while the canonical | * 12-month streaming Context is executing. | * | * This deliberatel`
- `N2`: `BLOCK:11|insert|A:265-264|R:511-560`
- `N2_REF`: `| /* | * Also capture here for any execution mode that closes | * during script evaluation itself. | */ | captureNativeClosedTrades(); | | /* | * BENCHTEST_V2_NATIVE_EQUITY_REAL_FI`
- `N3`: `BLOCK:14|insert|A:295-294|R:593-655`
- `N3_REF`: `/* | * Canonical V2 native ledger. | * Strategies retain their own Pine/Resin execution | * logic; no standardized indicator SL/TP is applied. | */ | executionModel: | &quot;NATIVE_STRA`
- `N4`: `UNKNOWN`
- `N4_REF`: `UNKNOWN`
- `NATIVE_BLOCK_IDS`: `8,11,14`
- `NATIVE_DIFF_BLOCKS`: `3`
- `PROD_DB_WRITE`: `NO`
- `REPO_CLEAN`: `YES`
- `REPO_WRITE`: `NO`
- `RESTART`: `NO`
