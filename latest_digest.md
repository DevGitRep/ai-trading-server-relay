# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T12:32:00.594404+00:00`
- Run ID: `20260911T123158Z`
- Step: `TRACE_APPROVED_TO_LIBRARY_PUBLICATION_BRIDGE`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `APPROVED_TYS_SOURCE_RECORD_PRESENT_BUT_FILTERED`
- Next gate: `TRACE_ONLY_EXACT_LIBRARY_INCLUDE_CONDITION`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CANDIDATES_MATCH_COUNT`: `1`
- `CANDIDATE_ID`: `ICL_SRC_A465DEED5818C8FA`
- `CLOUDFLARE_ACTION`: `NO`
- `CURRENT_MATCH_COUNT`: `NO_TABLE`
- `DB_WRITE`: `NO`
- `LIBRARY_LOADER_TRACE_LINE_COUNT`: `17`
- `LOADER1`: `L43:from_test_your_script_v1_import_(`
- `LOADER10`: `L129:FROM_sources`
- `LOADER11`: `L130:WHERE_(`
- `LOADER12`: `L163:_tys_filter_public_shas(`
- `LOADER13`: `L177:row[source_sha256]`
- `LOADER14`: `L250:sha_=_(row[source_sha256]_or_)`
- `LOADER15`: `L256:FROM_sources`
- `LOADER16`: `L257:WHERE_script_id_part=`
- `LOADER17`: `L318:_card[realistic_score]_=__metrics.get(realistic_score)`
- `LOADER2`: `L46:filter_public_shas_as`
- `LOADER3`: `L47:_tys_filter_public_shas,`
- `LOADER4`: `L53:_INDICATOR_LIBRARY_PUBLICATION_BATCH_V29L`
- `LOADER5`: `L56:_source_sha_cache_v1_already_provides_source_sha256.`
- `LOADER6`: `L68:_tys_filter_public_shas(`
- `LOADER7`: `L70:str(item[source_sha256])`
- `LOADER8`: `L72:if_item[source_sha256]`
- `LOADER9`: `L80:if_item[source_sha256]:`
- `PIPELINE_INDICATOR_ID`: `ICL_SRC_A465DEED5818C8FA`
- `PIPELINE_VERSIONS_MATCH_COUNT`: `1`
- `RESTART`: `NO`
- `ROW41_PUBLICATION`: `APPROVED`
- `SOURCE_CHANGE`: `NO`
