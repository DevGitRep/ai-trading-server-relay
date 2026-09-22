# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-22T01:13:22.367473+00:00`
- Run ID: `20260922T011320Z`
- Step: `CASE4OVERALLPATH`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CASE4_OVERALL_BAR_PATH_INSPECTED`
- Next gate: `PATCH_CASE4_OVERALL_EVENT_CONSTRUCTION`

## Facts

- `DASHBOARD_RESTART`: `NO`
- `F1`: `ALL LONG SHORT BAR REFERENCES`
- `F10`: `1169: var extraLong longBars.Where(x &gt;!expectedLong.Contains(x)).ToArray();`
- `F11`: `1170: var extraShort shortBars.Where(x &gt;!expectedShort.Contains(x)).ToArray();`
- `F12`: `1198: &amp;&amp; longBars.Count  expectedLong.Count`
- `F13`: `1199: &amp;&amp; shortBars.Count  expectedShort.Count;`
- `F14`: `1204: Console.WriteLine(&quot;LEAN_LONG &quot;+longBars.Count);`
- `F15`: `1205: Console.WriteLine(&quot;LEAN_SHORT &quot;+shortBars.Count);`
- `F16`: `MAIN LOOP CONTEXT`
- `F17`: `1060 new Assignment(name,node)`
- `F18`: `1061 );`
- `F19`: `1062`
- `F2`: `1078: var longBars new HashSet&lt;int&gt;();`
- `F20`: `1063 ctx.Series[name] new V[c.Length];`
- `F21`: `1064 }`
- `F22`: `1065`
- `F23`: `1066 // Six independent color source expressions.`
- `F24`: `1067 var sourceNodes new List&lt;Node&gt;();`
- `F25`: `1068`
- `F26`: `1069 foreach(var x in root.GetProperty(&quot;sources&quot;).EnumerateArray())`
- `F27`: `1070 {`
- `F28`: `1071 string expr x.GetProperty(&quot;expr&quot;).GetString()!;`
- `F29`: `1072 sourceNodes.Add(new Parser(expr).Parse());`
- `F3`: `1079: var shortBars new HashSet&lt;int&gt;();`
- `F30`: `1073 }`
- `F4`: `1139: if(longNow) longBars.Add(i);`
- `F5`: `1140: if(shortNow) shortBars.Add(i);`
- `F6`: `1163: int matchLong expectedLong.Count(x &gt;longBars.Contains(x));`
- `F7`: `1164: int matchShort expectedShort.Count(x &gt;shortBars.Contains(x));`
- `F8`: `1166: var missingLong expectedLong.Where(x &gt;!longBars.Contains(x)).ToArray();`
- `F9`: `1167: var missingShort expectedShort.Where(x &gt;!shortBars.Contains(x)).ToArray();`
- `HEAD`: `939755327f6d`
- `PRODUCTION_CODE_WRITES`: `0`
- `PRODUCTION_DB_WRITES`: `0`
- `REPO_CLEAN`: `YES`
