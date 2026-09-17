# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-17T17:49:12.272500+00:00`
- Run ID: `20260917T174909Z`
- Step: `GLOBAL31DIAG1`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `GLOBAL31DIAGNOSTICCOMPLETE`
- Next gate: `PATCHALLGLOBAL31FAILURES`

## Facts

- `DB_WRITE`: `NO`
- `DETAIL1`: `MappedArray.bottom_n_mask=AttributeError:Cannot resolve mapped values`
- `DETAIL2`: `MappedArray.idxmax=CONVERSION`
- `DETAIL3`: `MappedArray.idxmin=CONVERSION`
- `DETAIL4`: `MappedArray.nth_index=CONVERSION`
- `DETAIL5`: `MappedArray.top_n_mask=AttributeError:Cannot resolve mapped values`
- `DETAIL6`: `MappedArray.to_pd=[11, 2]&gt;[12, 2]`
- `FAIL1`: `MappedArray.bottom_n_mask,MappedArray.idxmax,MappedArray.idxmin,MappedArray.nth_index,MappedArray.top_n_mask,MappedArray.to_pd,ReturnsAccessor.rolling_annualized`
- `FAIL2`: `ReturnsAccessor.rolling_annualized_volatility,ReturnsAccessor.rolling_calmar_ratio,ReturnsAccessor.rolling_downside_risk,ReturnsAccessor.rolling_information_ratio`
- `FAIL3`: `ReturnsAccessor.rolling_omega_ratio,ReturnsAccessor.rolling_tail_ratio,ReturnsAccessor.rolling_total`
- `FAIL4`: `NONE`
- `FAILED_BY_CLASS`: `MappedArray:6,ReturnsAccessor:8`
- `FAILED_CHECKS`: `14`
- `HEAD`: `1c11c973bc91`
- `PASSED_CHECKS`: `16`
- `REPORT`: `global31_failure_diagnostic_v1.json`
- `RESTART`: `NO`
- `TOTAL_CHECKS`: `30`
