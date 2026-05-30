# Impossible Travel Investigation Runbook

## Objective

Investigate logins from geographically distant locations within a short time.

## Investigation Steps

1. Identify user account.
2. Review login locations.
3. Review timestamps.
4. Verify VPN usage.
5. Review device information.
6. Determine if credentials are compromised.

## Containment

- Reset password.
- Revoke active sessions.
- Require MFA re-registration.
- Block suspicious locations if necessary.

## Escalation

Escalate if:
- Login confirmed malicious.
- Sensitive account involved.
- Additional suspicious activity found.