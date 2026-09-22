# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-22T01:05:31.517613+00:00`
- Run ID: `20260922T010529Z`
- Step: `CASE4EXPORTSOURCEINSPECT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CASE4_SOURCE_EXPORT_INSERTION_INSPECTED`
- Next gate: `REPAIR_CASE4_SOURCE_EXPORT_PATCH`

## Facts

- `DASHBOARD_RESTART`: `NO`
- `HEAD`: `939755327f6d`
- `L1142`: `EMPTY`
- `L1143`: `for(int s 0;s&lt;sourceNodes.Count;s++)`
- `L1144`: `{`
- `L1145`: `Console.WriteLine(`
- `L1146`: `$&quot;SOURCE{s+1}_COUNTS {sourceLongBars[s].Count}/{sourceShortBars[s].Count}&quot;`
- `L1147`: `);`
- `L1148`: `EMPTY`
- `L1149`: `Console.WriteLine(`
- `L1150`: `$&quot;SOURCE{s+1}_TRACE {string.Join(&quot;,&quot;,earlyTrace[s])}&quot;`
- `L1151`: `// CASE4_SOURCE_BAR_EXPORT_V1`
- `L1152`: `var outDir   Path.GetDirectoryName(args[0]) ?? &quot;.&quot;;`
- `L1153`: `using(var bw   new BinaryWriter(File.Create(Path.Combine(outDir,$&quot;case4_cs_source{s+1}_long_i32.bin&quot;))))`
- `L1154`: `foreach(var x in sourceLongBars[s]) bw.Write(x);`
- `L1155`: `using(var bw   new BinaryWriter(File.Create(Path.Combine(outDir,$&quot;case4_cs_source{s+1}_short_i32.bin&quot;))))`
- `L1156`: `foreach(var x in sourceShortBars[s]) bw.Write(x);`
- `L1157`: `);`
- `L1158`: `}`
- `L1159`: `EMPTY`
- `L1160`: `var expectedLong ToSet(LoadInts(longPath));`
- `PRODUCTION_CODE_WRITES`: `0`
- `PRODUCTION_DB_WRITES`: `0`
- `REPO_CLEAN`: `YES`
