# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-08-28T17:14:15.864286+00:00`
- Run ID: `20260828T171413Z`
- Step: `REVIEWPRORUNTIMESCORESOURCE_V1B`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `PRO_RUNTIME_SCORE_SOURCE_RECONCILIATION_REVIEW_FAILED`
- Next gate: `REVIEW_PRO_RUNTIME_SCORE_RECONCILIATION_V1`

## Facts

- `CANONICAL_INTERNAL_SCORE`: `95.0`
- `CANONICAL_PRIVATE_SCORE`: `95.0`
- `CANONICAL_PRO_SCORE`: `95.0`
- `ERROR`: `RuntimeError_PINE_CATALOG_ROUTE_FUNCTION_MISSING`
- `EXISTING_ROUTE`: `/indicator-lab/pine-catalog/api`
- `FREE_SCORE`: `ABSENT`
- `M01`: `L10865:Verify the live route/runtime behavior before modifying the existing`
- `M02`: `L10873:tier projections.`
- `M03`: `L10929:The controller already imports the tier runtime.`
- `M04`: `L10931:The existing candidate report route already uses the tier runtime projection.`
- `M05`: `L10933:The existing Pine Catalog API already uses the tier runtime projection.`
- `M06`: `L10999:Preserve already working tier-runtime wiring.`
- `M07`: `L11075:`/indicator-lab/pine-catalog/api``
- `M08`: `L11077:continues to project its response through the entitlement runtime before`
- `MASTERFIRST`: `YES`
- `MASTER_RELEVANT_LINES`: `140`
- `TARGETED_READ`: `YES`
