# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-16T22:19:27.811772+00:00`
- Run ID: `20260916T221925Z`
- Step: `MAP_VECTORBT_MODULES_TO_ATB_QUANT_STACK`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `VECTORBT_MODULE_MAP_COMPLETE`
- Next gate: `BUILD_FIRST_GOLDEN_BEHAVIOR_TEST_FOR_SIGNAL_TO_TRADE_LIFECYCLE`

## Facts

- `ATB_CHANGED`: `NO`
- `BROADCAST`: `_engine.py:broadcast_to_shape;_engine.py:broadcast_2d_to_shape;params.py:broadcast_params;accessors.py:broadcast;accessors.py:broadcast_to`
- `DB_WRITES`: `0`
- `DRAWDOWN`: `enums.py:DrawdownStatusT;drawdowns.py:Drawdowns;nb.py:drawdown_1d_nb;nb.py:drawdown_nb;nb.py:max_drawdown_1d_nb`
- `FAILURE`: `NONE`
- `FROM_SIGNALS_CALLS`: `listbroadcastable_args.keys.index;broadcast;np.broadcast_to;nb.simulate_from_signal_func_nb;broadcastable_args.values;broadcastable_args.keys;dispatch.simulate_from_signals`
- `FROM_SIGNALS_LINE`: `2048`
- `FROM_SIGNALS_PATH`: `vectorbt/portfolio/base.py`
- `INTERNAL_RC`: `0`
- `ORDERS`: `enums.py:RejectedOrderError;enums.py:OrderStatusT;enums.py:OrderSideT;enums.py:OrderStatusInfoT;enums.py:ProcessOrderState`
- `PARAMS`: `params.py:flatten_param_tuples;params.py:create_param_combs;params.py:broadcast_params;params.py:create_param_product`
- `PORTFOLIO`: `base.py:Portfolio;nb.py:simulate_from_orders_nb;nb.py:simulate_from_signals_nb;nb.py:simulate_from_signal_func_nb;nb.py:simulate_nb`
- `RECORDS`: `base.py:RecordsWithFields;base.py:MetaRecords;base.py:Records;col_mapper.py:ColumnMapper;mapped_array.py:MetaMappedArray`
- `REFERENCE_CHANGED`: `NO`
- `RETURNS`: `accessors.py:ReturnsAccessor;accessors.py:ReturnsSRAccessor;accessors.py:ReturnsDFAccessor;nb.py:returns_1d_nb;nb.py:returns_nb`
- `SIGNALS`: `enums.py:StopTypeT;factory.py:SignalFactory;accessors.py:SignalsAccessor;accessors.py:SignalsSRAccessor;accessors.py:SignalsDFAccessor`
- `STATS`: `stats_builder.py:MetaStatsBuilderMixin;stats_builder.py:StatsBuilderMixin;base.py:stats_defaults;base.py:stats_defaults;nb.py:update_open_pos_stats_nb`
- `STOPS`: `enums.py:StopTypeT;enums.py:StopEntryPriceT;enums.py:StopExitPriceT;enums.py:StopExitModeT;enums.py:StopUpdateModeT`
- `TRADES`: `enums.py:TradeDirectionT;enums.py:TradeStatusT;enums.py:TradesTypeT;trades.py:Trades;trades.py:EntryTrades`
