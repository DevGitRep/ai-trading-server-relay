# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T12:06:28.826135+00:00`
- Run ID: `20260911T120626Z`
- Step: `INSPECT_ROW41_APPROVAL_CONTROL`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `ROW41_LIBRARY_CONTROL_RENDERED_DISABLED`
- Next gate: `PATCH_ONLY_CONTROL_ENABLE_CONDITION_FOR_VALID_REVIEW_ROW`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `HTTP`: `200`
- `LIVE_APPROVAL_WORDS`: `Library,approve,approved`
- `LIVE_CHECKBOX_PRESENT`: `YES`
- `LIVE_DISABLED`: `YES`
- `LIVE_FORM_PRESENT`: `YES`
- `RESTART`: `NO`
- `ROW41_PRESENT`: `YES`
- `ROW41_PUBLICATION`: `PRIVATE`
- `ROW41_REVIEW_ALLOWED`: `1`
- `ROW41_SUBMISSION`: `TYS_52A5CE02E0444D05BFED31AFD52665C5`
- `SOURCE1`: `L54:approved_=_(`
- `SOURCE10`: `L165:p.library_publication_status,`
- `SOURCE11`: `L166:t.library_publication_status`
- `SOURCE12`: `L215:WHERE_t.library_review_allowed=1`
- `SOURCE13`: `L296:approved:_(`
- `SOURCE14`: `L301:==_APPROVED`
- `SOURCE15`: `L375:input[type=checkbox]{`
- `SOURCE16`: `L429:name=approved`
- `SOURCE2`: `L57:approved`
- `SOURCE3`: `L67:library_review_allowed,`
- `SOURCE4`: `L81:row[library_review_allowed]`
- `SOURCE5`: `L86:if_approved:`
- `SOURCE6`: `L103:APPROVED`
- `SOURCE7`: `L104:if_approved`
- `SOURCE8`: `L118:library_publication_status=,`
- `SOURCE9`: `L133:library_publication_status=,`
- `SOURCE_CHANGE`: `NO`
- `SOURCE_HIT_COUNT`: `20`
