# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-17T12:36:13.136521+00:00`
- Run ID: `20260917T123611Z`
- Step: `TRACE_DRAWDOWN_SEMANTICS`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `DRAWDOWN_SEMANTICS_TRACED`
- Next gate: `IMPLEMENT_NATIVE_DRAWDOWNS_CORE_GOLDEN_PARITY`

## Facts

- `ATB_CHANGED`: `NO`
- `DASHBOARD_RESTART`: `NO`
- `DB_WRITES`: `0`
- `FAILURE`: `NONE`
- `FIRST_RECORD`: `Column:_0,_Drawdown_Id:_0,_End_Timestamp:_2024-01-06T00:00:00,_End_Value:_112.0,_Peak_Timestamp:_2024-01-02T00:00:00,_`
- `INTERNAL_RC`: `0`
- `LAST_RECORD`: `Column:_0,_Drawdown_Id:_3,_End_Timestamp:_2024-01-15T00:00:00,_End_Value:_108.0,_Peak_Timestamp:_2024-01-12T00:00:00,_`
- `METRIC_ACTIVE_DRAWDOWN`: `-0.1`
- `METRIC_ACTIVE_DURATION`: `3_days_00:00:00`
- `METRIC_ACTIVE_RECOVERY`: `0.0`
- `METRIC_ACTIVE_RECOVERY_DURATION`: `0_days_00:00:00`
- `METRIC_ACTIVE_RECOVERY_RETURN`: `0.0`
- `METRIC_AVG_DRAWDOWN`: `-0.09839603331451158`
- `METRIC_AVG_DURATION`: `2_days_06:00:00`
- `METRIC_AVG_RECOVERY_RETURN`: `0.09849830999517142`
- `METRIC_COUNT`: `4`
- `METRIC_COVERAGE`: `0.6`
- `METRIC_MAX_DRAWDOWN`: `-0.13636363636363635`
- `METRIC_MAX_DURATION`: `3_days_00:00:00`
- `METRIC_NAMES`: `active_drawdown,active_duration,active_recovery,active_recovery_duration,active_recovery_return,avg_drawdown,avg_durat`
- `MISSING_SOURCE`: `avg_duration,coverage,max_duration`
- `READ_ONLY`: `YES`
- `RECORD_FIELDS`: `Column,Drawdown_Id,End_Timestamp,End_Value,Peak_Timestamp,Peak_Value,Start_Timestamp,Status,Valley_Timestamp,Valley_Va`
- `SRC_ACTIVE_DRAWDOWN`: `return_self.wrapper.wrap_reduced(curr_drawdown,_group_by=group_by,_**wrap_kwargs)`
- `SRC_ACTIVE_DURATION`: `return_self.active.duration.nth(-1,_group_by=group_by,_wrap_kwargs=wrap_kwargs,_**kwargs)`
- `SRC_ACTIVE_RECOVERY`: `return_self.wrapper.wrap_reduced(curr_recovery,_group_by=group_by,_**wrap_kwargs)`
- `SRC_ACTIVE_RECOVERY_DURATION`: `return_self.active.recovery_duration.nth(-1,_group_by=group_by,_wrap_kwargs=wrap_kwargs,_**kwargs)`
- `SRC_ACTIVE_RECOVERY_RETURN`: `return_self.active.recovery_return.nth(-1,_group_by=group_by,_wrap_kwargs=wrap_kwargs,_**kwargs)`
- `SRC_AVG_DRAWDOWN`: `return_self.drawdown.mean(group_by=group_by,_wrap_kwargs=wrap_kwargs,_**kwargs)`
- `SRC_AVG_RECOVERY_RETURN`: `return_self.recovery_return.mean(group_by=group_by,_wrap_kwargs=wrap_kwargs,_**kwargs)`
- `SRC_MAX_DRAWDOWN`: `return_self.drawdown.min(group_by=group_by,_wrap_kwargs=wrap_kwargs,_**kwargs)`
- `VECTORBT_VERSION`: `1.1.0`
