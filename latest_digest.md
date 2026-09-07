# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-07T10:25:11.014884+00:00`
- Run ID: `20260907T102509Z`
- Step: `PROVEPRIMARYSECONDARYSCORE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `PRIMARYSECONDARYSCORINGSEMANTICSRESOLVED`
- Next gate: `ENFORCEFROZENPRIMARYREALISTICSCORE`

## Facts

- `BENCHTEST_RERUN`: `NO`
- `CALL1`: `_v2_score_one( primary, role=&quot;PRIMARY_CROSS_TYPE&quot;, )`
- `CALL2`: `_v2_score_one( secondary, role=secondary_role, )`
- `CALLOWNER1`: `primary_score=_v2_score_one( primary, role=&quot;PRIMARY_CROSS_TYPE&quot;, )`
- `CALLOWNER2`: `secondary_score=_v2_score_one( secondary, role=secondary_role, )`
- `CHANGES_MADE`: `NO`
- `CURRENT`: `16`
- `DB_WRITE`: `NO`
- `FALLBACK1`: `IFEXP:&quot;INDICATOR_SECONDARY_TYPE_SPECIFIC&quot; if script_kind==&quot;indicator&quot; else &quot;STRATEGY_SECONDARY_TYPE_SPECIFIC&quot;`
- `FALLBACKN`: `1`
- `FROZEN_PRIMARY`: `UNIVERSAL_SIGNAL_FLIP_V2`
- `FROZEN_SECONDARY`: `STANDARDIZED_ATR_1R_1_5R_V2`
- `MASTER_READ`: `YES`
- `PREFLIGHT_RERUN`: `NO`
- `PRIMARYSCOREVAR`: `primary_score=_v2_score_one( primary, role=&quot;PRIMARY_CROSS_TYPE&quot;, )`
- `PRIMARYTRADES`: `0`
- `QUICK`: `ok`
- `REALISTICEXPR`: `primary_score[ &quot;score&quot; ]`
- `RESTART`: `NO`
- `RETURNREALISTIC`: `primary_score[ &quot;score&quot; ]`
- `RETURNSECONDARY`: `secondary_score[ &quot;score&quot; ]`
- `SCORECALLN`: `2`
- `SECONDARYSCOREVAR`: `secondary_score=_v2_score_one( secondary, role=secondary_role, )`
- `SECONDARYTRADES`: `15833`
- `SECONDARY_MAY_REPLACE_PRIMARY`: `NO`
- `SOURCE_CHANGE`: `NO`
- `ZEROID`: `ICL_LIB_4B7C809FCA83500F`
- `ZEROSCORE`: `8.487595661182382`
