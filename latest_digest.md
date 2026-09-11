# Latest sanitized server digest

- Relay version: `SERVER_RELAY_V0B`
- Published UTC: `2026-09-11T06:46:23.331700+00:00`
- Run ID: `20260911T064621Z`
- Step: `INSPECT_EARLIER_WORKING_MAIL_IMPLEMENTATION_CONFIG`
- Status: `SUCCESS`
- Exit code: `0`
- Verdict: `EARLIER_OR_SHARED_MAIL_IMPLEMENTATION_FOUND`
- Next gate: `COMPARE_WORKING_MAIL_CONFIG_WITH_V15`

## Facts

- `BENCHTEST_RUN`: `NO`
- `CLOUDFLARE_ACTION`: `NO`
- `DB_WRITE`: `NO`
- `EMAIL_CONFIG_FUNCTIONS`: `9`
- `EMAIL_FUNCTIONS`: `49`
- `MAIL_REFERENCE_FILES`: `15`
- `OLDER_CONFIG_FUNCTIONS`: `0`
- `OLDER_EMAIL_FUNCTIONS`: `40`
- `OLD_EMAIL1`: `test_your_script_v1.py:_tys_ensure_email_columns_v15:657`
- `OLD_EMAIL2`: `test_your_script_v1.py:_tys_set_email_state_v15:665`
- `OLD_EMAIL3`: `test_your_script_v1.py:_tys_email_config_v15:687`
- `OLD_EMAIL4`: `test_your_script_v1.py.pre_benchtest_stdout_capture:_tys_ensure_email_columns_v15:507`
- `REF1`: `test_your_script_v1.py:SMTP_HOST_SMTP_FROM_EMAIL_PUBLIC_BASE_URL_smtplib_SMTP__SMTP_SSL_`
- `REF2`: `test_your_script_v1.py.pre_benchtest_stdout_capture:SMTP_HOST_SMTP_FROM_EMAIL_PUBLIC_BASE_URL_smtplib_SMTP__SMTP_SSL_`
- `REF3`: `test_your_script_v1.py.pre-techfix-20260910T093024Z:SMTP_HOST_SMTP_FROM_EMAIL_PUBLIC_BASE_URL_smtplib_SMTP__SMTP_SSL_`
- `REF4`: `test_your_script_v1.py.pre-techstatus-20260910T102005Z:SMTP_HOST_SMTP_FROM_EMAIL_PUBLIC_BASE_URL_smtplib_SMTP__SMTP_SSL_`
- `REF5`: `test_your_script_v1.py.bak-techfix:SMTP_HOST_SMTP_FROM_EMAIL_PUBLIC_BASE_URL_smtplib_SMTP__SMTP_SSL_`
- `RESTART`: `NO`
- `SCANNED_SOURCE_FILES`: `22351`
- `SHARED_HELPER1`: `test_your_script_v1.py:_tys_send_smtp_v15:721`
- `SHARED_HELPER2`: `test_your_script_v1.py.pre_benchtest_stdout_capture:_tys_send_smtp_v15:571`
- `SHARED_HELPER3`: `test_your_script_v1.py.pre-techfix-20260910T093024Z:_tys_send_smtp_v15:2163`
- `SHARED_HELPER4`: `test_your_script_v1.py.pre-techstatus-20260910T102005Z:_tys_send_smtp_v15:2190`
- `SHARED_MAIL_HELPERS`: `9`
- `SOURCE_CHANGE`: `NO`
- `VALUES_EXPOSED`: `NO`
