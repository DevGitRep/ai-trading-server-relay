# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-17T17:39:29.048343+00:00`
- Run ID: `20260917T173831Z`
- Step: `GLOBALQUANTAUDIT1`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `GLOBALQUANTAUDITCOMPLETE`
- Next gate: `IMPLEMENTALLTRUEQUANTGAPS`

## Facts

- `CLASSES`: `Drawdowns,EntryTrades,ExitTrades,MappedArray,Orders,Portfolio,Positions,Ranges,Records,ReturnsAccessor,Trades`
- `DB_WRITE`: `NO`
- `EXACT_COUNT`: `288`
- `FUNCTIONAL_COUNT`: `665`
- `GAP1`: `Drawdowns.active,Drawdowns.closed,Drawdowns.col,Drawdowns.decline_duration,Drawdowns.deep_getattr,Drawdowns.end_idx,Drawdowns.end_val,Drawdowns.id,Drawdowns.indexing_func_meta,Drawdowns.open`
- `GAP2`: `Drawdowns.override_field_config_doc,Drawdowns.override_metrics_doc,Drawdowns.override_subplots_doc,Drawdowns.peak_idx,Drawdowns.peak_val,Drawdowns.post_resolve_attr`
- `GAP3`: `Drawdowns.pre_resolve_attr,Drawdowns.recovered,Drawdowns.start_idx,Drawdowns.stats,Drawdowns.status,Drawdowns.to_doc,Drawdowns.to_mask,Drawdowns.update_config,Drawdowns.valley_idx`
- `GAP4`: `Drawdowns.valley_val,Drawdowns.xs,EntryTrades.closed,EntryTrades.col,EntryTrades.deep_getattr,EntryTrades.direction,EntryTrades.end_idx,EntryTrades.entry_fees,EntryTrades.entry_idx`
- `GAP5`: `EntryTrades.entry_price,EntryTrades.exit_fees,EntryTrades.exit_idx,EntryTrades.exit_price,EntryTrades.id,EntryTrades.indexing_func_meta,EntryTrades.long,EntryTrades.open`
- `HEAD`: `1c11c973bc91`
- `PACK`: `global_vectorbt_quant_gap_pack_v1.json`
- `PROBEABLE_COUNT`: `259`
- `PUBLIC_COUNT`: `884`
- `REPORT`: `global_vectorbt_quant_audit_v1.json`
- `REPO_CLEAN`: `YES`
- `RESTART`: `NO`
- `REVIEW_COUNT`: `376`
- `WRAPPER_COUNT`: `1`
