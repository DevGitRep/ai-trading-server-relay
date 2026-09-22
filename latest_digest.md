# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-22T07:57:41.640394+00:00`
- Run ID: `20260922T075739Z`
- Step: `CASE4S3NUMERICINSPECT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CASE4_S3_NUMERIC_SEMANTICS_INSPECTED`
- Next gate: `COMPARE_CASE4_S3_NUMERIC_TRACE`

## Facts

- `DASHBOARD_RESTART`: `NO`
- `F1`: `SMA IMPLEMENTATION`
- `F10`: `402: int len (int)Math.Round(args[1].Eval(c).AsNum());`
- `F11`: `1007: string marketPath args[1];`
- `F12`: `COMPARISON OPERATORS`
- `F13`: `53: new(StringComparer.Ordinal);`
- `F14`: `56: new(StringComparer.Ordinal);`
- `F15`: `59: new(StringComparer.Ordinal);`
- `F16`: `730: var n Compare();`
- `F17`: `736: n new BinNode(op,n,Compare());`
- `F18`: `742: Node Compare()`
- `F19`: `961: using var br new BinaryReader(File.OpenRead(path));`
- `F2`: `377: if(name  &quot;ta.sma&quot;)`
- `F20`: `1160: using(var bw   new BinaryWriter(File.Create(Path.Combine(outDir,$&quot;case4_cs_source{s+1}_long_i32.bin&quot;))))`
- `F21`: `1162: using(var bw   new BinaryWriter(File.Create(Path.Combine(outDir,$&quot;case4_cs_source{s+1}_short_i32.bin&quot;))))`
- `F22`: `NONE`
- `F23`: `NONE`
- `F24`: `NONE`
- `F25`: `NONE`
- `F26`: `NONE`
- `F27`: `NONE`
- `F28`: `NONE`
- `F3`: `HISTORY INDEXING`
- `F4`: `318: args[1].Eval(c).AsNum(),`
- `F5`: `327: args[1].Eval(c).AsNum()`
- `F6`: `335: args[1].Eval(c).AsNum()`
- `F7`: `351: args[1].Eval(c).AsNum()`
- `F8`: `357: int len (int)Math.Round(args[1].Eval(c).AsNum());`
- `F9`: `380: int len (int)Math.Round(args[1].Eval(c).AsNum());`
- `HEAD`: `939755327f6d`
- `PRODUCTION_CODE_WRITES`: `0`
- `PRODUCTION_DB_WRITES`: `0`
- `REPO_CLEAN`: `YES`
