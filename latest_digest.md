# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-08T10:05:28.479484+00:00`
- Run ID: `20260908T100526Z`
- Step: `READMARKERWIRE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `MARKERWIREREAD`
- Next gate: `PATCHMARKERWIRE`

## Facts

- `ACTION1`: `const kind=String( marker[2]||&quot;&quot; ).toUpperCase()`
- `ACTION2`: `const direction=String( marker[3]||&quot;&quot; ).toUpperCase()`
- `ACTION3`: `const shortTrade= direction.includes( &quot;SHORT&quot; )`
- `ACTION4`: `if(shortTrade){ return kind===&quot;ENTRY&quot; ?&quot;SELL&quot; :&quot;BUY&quot;`
- `BENCHTEST_RERUN`: `NO`
- `COUNT1`: `const buyMarkerCount=`
- `COUNT2`: `const sellMarkerCount=`
- `DB_WRITE`: `NO`
- `INDEX1`: `rAction=marker=&gt;{ const kind=String( marker[2]||&quot;&quot; ).toUpperCase(); const direction=String( marker[3]||&quot;`
- `INDEX2`: `pperCase(); const direction=String( marker[3]||&quot;&quot; ).toUpperCase(); const shortTrade= direction.includes`
- `INDEX3`: `rker=&gt;{ const mt=Number( marker[0] ); const mp=Number( marker[1]`
- `INDEX4`: `); const mp=Number( marker[1] ); if( !Number.isFinite(mt)`
- `MASTER_CHANGE`: `NO`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `RENDER1`: `markerAction(marker)===&quot;BUY&quot;`
- `RENDER2`: `markerAction(marker)===&quot;SELL&quot;`
- `RENDER3`: `markerAction(`
- `RENDER4`: `NONE`
- `RESTART`: `NO`
- `SCORE_PRODUCER_CHANGE`: `NO`
- `SOURCE_CHANGE`: `NO`
