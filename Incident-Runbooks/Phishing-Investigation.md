# Phishing Investigation Runbook

## Objective

Investigate suspected phishing emails.

## Investigation Steps

1. Identify sender.
2. Analyze email headers.
3. Review embedded URLs.
4. Analyze attachments.
5. Search for additional recipients.
6. Determine whether credentials were submitted.
7. Review Defender alerts.

## Containment

- Remove emails from mailboxes.
- Block sender domain.
- Reset compromised credentials.
- Enable MFA.

## Escalation

Escalate if:
- Multiple users clicked links.
- Malware was delivered.
- Credentials were stolen.