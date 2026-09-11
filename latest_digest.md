# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T07:38:20.837737+00:00`
- Run ID: `20260911T073818Z`
- Step: `TRACE_REGISTER_ARGUMENT_EXPRESSION`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `REGISTER_HOST_ARGUMENT_EXACTLY_IDENTIFIED`
- Next gate: `INSPECT_HOST_ARGUMENT_DEFINITION_ONLY`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `DEF1`: `FUNCTION:14892:def__aitb_is_public_host_v1():_host_=_(_str(request.host_or_&quot;&quot;)_.split(&quot;:&quot;,_1)[0]_.strip()_.lower()_.rstrip(&quot;.&quot;)_)_return_host_in__AITB_PUBLIC_HOSTS_V1`
- `ENCLOSING_SCOPE`: `MODULE`
- `HOST_ARG_DEF_COUNT`: `1`
- `HOST_ARG_EXPR`: `_aitb_is_public_host_v1`
- `HOST_ARG_NAME`: `_aitb_is_public_host_v1`
- `HOST_ARG_NODE_TYPE`: `Name`
- `PUBLIC_HOST_BLOCKED`: `YES`
- `REGISTER_CALL_COUNT`: `1`
- `RESTART`: `NO`
- `REVIEW_ELIGIBLE`: `YES`
- `SOURCE_CHANGE`: `NO`
