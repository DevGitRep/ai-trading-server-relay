# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-15T11:12:55.576697+00:00`
- Run ID: `20260915T111253Z`
- Step: `INSPECT_STRIPE_WEBHOOK_CONTRACT`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `STRIPE_WEBHOOK_CONTRACT_IDENTIFIED`
- Next gate: `CONFIGURE_STRIPE_TEST_DASHBOARD_AND_ENV`

## Facts

- `ENV_NAMES`: `ATB_PUBLIC_BASE_URL,STRIPE_SECRET_KEY,STRIPE_WEBHOOK_SECRET`
- `ENV_NAME_COUNT`: `3`
- `EVENTS`: `checkout.session.async_payment_failed,checkout.session.async_payment_succeeded,checkout.session.completed`
- `EVENT_COUNT`: `3`
- `WEBHOOK_ROUTE`: `NONE`
- `WEBHOOK_URL`: `NONE`
