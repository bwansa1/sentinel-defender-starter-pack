# Brute Force Investigation Runbook

## Objective

Investigate repeated failed login attempts against user accounts.

## Investigation Steps

1. Identify the affected user account.
2. Review failed login count.
3. Review source IP addresses.
4. Verify geolocation of login attempts.
5. Determine whether MFA is enabled.
6. Review successful logins after failures.
7. Check for account lockouts.

## Containment

- Reset password.
- Revoke active sessions.
- Block malicious IP addresses.
- Enable MFA.

## Escalation

Escalate if:
- Privileged account involved.
- Multiple users targeted.
- Successful compromise confirmed.