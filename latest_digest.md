# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-19T17:58:07.027359+00:00`
- Run ID: `20260919T175805Z`
- Step: `RESOLVEATBPORTFOLIOAPI325`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `ATBPORTFOLIOAPIRESOLVED`
- Next gate: `EXECUTEFULLATBSUITENAMINGMIGRATION`

## Facts

- `CALLABLE_CANDIDATES`: `atb_quant_engine.backtestingpy_execution_contract(),atb_quant_engine.extract_signal_provenance(*sources:_&#x27;Any&#x27;)_-&gt;_&#x27;dict[str,_Any]&#x27;`
- `CODE_WRITE`: `NO`
- `COMMIT`: `NO`
- `DB_WRITE`: `NO`
- `ENGINE_HAS_PORTFOLIO`: `NO`
- `HEAD`: `e40f9755c8a3`
- `HIT_1`: `tools/atb_quant_engine/lifecycle.py:L73:Position_sizing,_fees,_stops,_targets,_conflicts_and_portfolio_accounting`
- `HIT_2`: `tools/atb_quant_engine/portfolio.py:L1:&quot;&quot;&quot;ATB_native_portfolio_simulation.`
- `HIT_3`: `tools/atb_quant_engine/portfolio.py:L64:-_portfolio_value_=_cash_+_marked-to-market_position`
- `HIT_4`: `tools/atb_quant_engine/portfolio.py:L169:#_===_VectorBT-compatible_Portfolio_state_foundation_===`
- `PUSH`: `NO`
- `RESTART`: `NO`
- `SOURCE_HIT_COUNT`: `18`
- `SURFACE_HAS_PORTFOLIO`: `NO`
- `SURFACE_PORTFOLIO_FROM_SIGNALS`: ``
- `SURFACE_RUNTIME_NAMES`: ``
