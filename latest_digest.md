# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-18T18:58:42.243315+00:00`
- Run ID: `20260918T185840Z`
- Step: `INSPECTALREADYTESTED223`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `ALREADYTESTEDLOGICREAD`
- Next gate: `PROVEMISSING81MISMATCH`

## Facts

- `ALREADY_TESTED_END`: `67`
- `ALREADY_TESTED_LINE`: `44`
- `COMMIT`: `NO`
- `DB_WRITE`: `NO`
- `HEAD`: `398294cb1bc9`
- `LOGIC1`: `44:def already_tested(conn, sha):`
- `LOGIC2`: `47:SELECT 1`
- `LOGIC3`: `48:FROM candidates`
- `LOGIC4`: `49:WHERE source_sha256:?`
- `LOGIC5`: `53:OR conversion_status IS NOT NULL`
- `LOGIC6`: `54:OR causality_status IS NOT NULL`
- `LOGIC7`: `55:OR repaint_status IS NOT NULL`
- `LOGIC8`: `56:OR parity_status IS NOT NULL`
- `LOGIC_FACTS`: `14`
- `REPO_CLEAN`: `YES`
- `REPO_WRITE`: `NO`
- `RESTART`: `NO`
