# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-22T00:57:15.436097+00:00`
- Run ID: `20260922T005713Z`
- Step: `CASE4INSPECTCSCOLOR`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `CASE4_CSHARP_COLOR_CLASSIFIER_INSPECTED`
- Next gate: `PATCH_CASE4_CANONICAL_COLOR_CLASSIFICATION`

## Facts

- `CS1`: `10:enum VK { NA, Num, Bool, Color, Str }`
- `CS10`: `120: return V.Color(&quot;OTHER&quot;);`
- `CS11`: `198: (x.K  VK.Color    x.K  VK.Str)`
- `CS12`: `199: &amp;&amp; (y.K  VK.Color    y.K  VK.Str)`
- `CS13`: `289: static V ColorRgb(double rd,double gd,double bd)`
- `CS14`: `296: return V.Color(&quot;GREEN&quot;);`
- `CS15`: `299: return V.Color(&quot;RED&quot;);`
- `CS16`: `301: return V.Color(&quot;OTHER&quot;);`
- `CS2`: `28: public static V Color(string x)  &gt; new(VK.Color,0,false,x);`
- `CS3`: `41: public string ColorState()  &gt;`
- `CS4`: `42: K  VK.Color ? S : &quot;NONE&quot;;`
- `CS5`: `110: if(name.StartsWith(&quot;color.&quot;,StringComparison.Ordinal))`
- `CS6`: `114: if(n.Contains(&quot;green&quot;)    n.Contains(&quot;lime&quot;)    n.Contains(&quot;teal&quot;))`
- `CS7`: `115: return V.Color(&quot;GREEN&quot;);`
- `CS8`: `117: if(n.Contains(&quot;red&quot;)    n.Contains(&quot;maroon&quot;))`
- `CS9`: `118: return V.Color(&quot;RED&quot;);`
- `DASHBOARD_RESTART`: `NO`
- `HEAD`: `939755327f6d`
- `PRODUCTION_CODE_WRITES`: `0`
- `PRODUCTION_DB_WRITES`: `0`
- `REPO_CLEAN`: `YES`
