# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-17T11:08:24.477899+00:00`
- Run ID: `20260917T110652Z`
- Step: `MAP_ZERO_THRESHOLD_AND_RETURNS_CORE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `ZERO_THRESHOLD_AND_RETURNS_CORE_MAPPED`
- Next gate: `IMPLEMENT_ZERO_THRESHOLD_AND_CREATE_RETURNS_GOLDENS`

## Facts

- `ATB_CHANGED`: `NO`
- `DASHBOARD_RESTART`: `NO`
- `DB_WRITES`: `0`
- `DIRECTION_COUNTS`: `ZERO_CROSS_LONG:4,ZERO_CROSS_SHORT:4,THRESHOLD_CROSS_LONG:3,THRESHOLD_CROSS_SHORT:3`
- `FAILURE`: `NONE`
- `INTERNAL_RC`: `0`
- `READ_ONLY`: `YES`
- `RETURNS_ANNUALIZED`: `args=self,engine,wrap_kwargsdefaults=2`
- `RETURNS_ANNUALIZED_VOLATILITY`: `args=self,levy_alpha,ddof,engine,wrap_kwargsdefaults=4`
- `RETURNS_CALMAR_RATIO`: `args=self,engine,wrap_kwargsdefaults=2`
- `RETURNS_CUMULATIVE`: `args=self,start_value,engine,wrap_kwargsdefaults=3`
- `RETURNS_MAX_DRAWDOWN`: `args=self,engine,wrap_kwargsdefaults=2`
- `RETURNS_SHARPE_RATIO`: `args=self,risk_free,ddof,engine,wrap_kwargsdefaults=4`
- `RETURNS_SORTINO_RATIO`: `args=self,required_return,engine,wrap_kwargsdefaults=3`
- `THRESHOLD_CROSS_TOTAL`: `6`
- `THRESHOLD_EXAMPLE`: `PINER::THRESHOLD_CROSS|plot:0:RSI|hline:2:hline_2:50|FOLLOW::LONG`
- `THRESHOLD_PATTERNS`: `plots=1hlines=1dir=LONG:3,plots=1hlines=1dir=SHORT:3`
- `THRESHOLD_RUNTIME_PLOT_OK`: `6`
- `THRESHOLD_SOURCE_SEMANTICS`: `NONE`
- `THRESHOLD_VALUES`: `50.0:4,0.0:2`
- `ZERO_CROSS_TOTAL`: `8`
- `ZERO_EXAMPLE`: `PINER::ZERO_CROSS|plot:0:SMI_Ergodic_Histogram|FOLLOW::LONG`
- `ZERO_PATTERNS`: `plots=1hlines=0dir=LONG:4,plots=1hlines=0dir=SHORT:4`
- `ZERO_RUNTIME_PLOT_OK`: `8`
- `ZERO_SOURCE_SEMANTICS`: `GT_ZERO:6,LT_ZERO:4,CROSSOVER_ZERO:2,CROSSUNDER_ZERO:2`
