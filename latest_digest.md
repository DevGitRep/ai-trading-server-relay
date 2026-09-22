# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-22T01:08:26.909552+00:00`
- Run ID: `20260922T010824Z`
- Step: `CASE4UNIONINSPECT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CASE4_OVERALL_SIGNAL_AGGREGATION_INSPECTED`
- Next gate: `PATCH_CASE4_OVERALL_SIGNAL_AGGREGATION`

## Facts

- `DASHBOARD_RESTART`: `NO`
- `F1`: `41: public string ColorState()  &gt;`
- `F10`: `1132: sourceShortBars[s].Add(i);`
- `F11`: `1139: if(longNow) longBars.Add(i);`
- `F12`: `1140: if(shortNow) shortBars.Add(i);`
- `F13`: `1146: $&quot;SOURCE{s+1}_COUNTS {sourceLongBars[s].Count}/{sourceShortBars[s].Count}&quot;`
- `F14`: `1155: foreach(var x in sourceLongBars[s]) bw.Write(x);`
- `F15`: `1157: foreach(var x in sourceShortBars[s]) bw.Write(x);`
- `F16`: `NONE`
- `F17`: `NONE`
- `F18`: `NONE`
- `F19`: `NONE`
- `F2`: `1082: var sourceLongBars   Enumerable`
- `F20`: `NONE`
- `F21`: `NONE`
- `F22`: `NONE`
- `F23`: `NONE`
- `F24`: `NONE`
- `F3`: `1087: var sourceShortBars   Enumerable`
- `F4`: `1106: bool longNow false;`
- `F5`: `1107: bool shortNow false;`
- `F6`: `1111: string cur sourceNodes[s].Eval(ctx).ColorState();`
- `F7`: `1125: longNow true;`
- `F8`: `1126: sourceLongBars[s].Add(i);`
- `F9`: `1131: shortNow true;`
- `HEAD`: `939755327f6d`
- `PRODUCTION_CODE_WRITES`: `0`
- `PRODUCTION_DB_WRITES`: `0`
- `REPO_CLEAN`: `YES`
