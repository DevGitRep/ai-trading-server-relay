# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-17T17:22:33.190779+00:00`
- Run ID: `20260917T172230Z`
- Step: `PORTFOLIOPOSTPATCHDIAG1`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `POSTPATCHDIAGNOSTICCOMPLETE`
- Next gate: `PATCHREMAININGPORTFOLIOFAILURES`

## Facts

- `DB_WRITE`: `NO`
- `DETAIL1`: `ungrouped:annual_returns=-0.00029636100780916497&gt;-0.00035454313316229946`
- `DETAIL2`: `ungrouped:deflated_sharpe_ratio=1.0&gt;0.09781980130752949`
- `DETAIL3`: `grouped:annual_returns=0.012254606551482805&gt;0.012225515488806904`
- `DETAIL4`: `grouped:deflated_sharpe_ratio=1.0&gt;nan`
- `FAILED_CHECKS`: `4`
- `FAILED_LABELS`: `ungrouped:annual_returns,ungrouped:deflated_sharpe_ratio,grouped:annual_returns,grouped:deflated_sharpe_ratio`
- `FAILED_METHODS`: `annual_returns,deflated_sharpe_ratio`
- `HEAD`: `d250109b29e5`
- `PASSED_CHECKS`: `12`
- `REPORT`: `portfolio_postpatch_five_diagnostic_v1.json`
- `RESTART`: `NO`
- `TOTAL_CHECKS`: `16`
