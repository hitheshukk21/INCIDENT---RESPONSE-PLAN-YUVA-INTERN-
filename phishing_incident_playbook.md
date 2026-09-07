# Phishing / Account Compromise Playbook

## Scenario
An employee enters corporate credentials into a phishing website. The SOC later detects an unusual login.

## Detection
- Review email security alert/report.
- Check identity-provider login history.
- Review mailbox rules and forwarding.
- Identify affected account and first suspicious activity.

## Containment
- Disable or restrict the account if necessary.
- Revoke active sessions/tokens.
- Reset credentials through a trusted process.
- Verify/enforce MFA.
- Block phishing domains/URLs.
- Search for other users who may have received the same campaign.

## Investigation
- Build a timeline.
- Review identity, email, endpoint, and network logs.
- Identify unauthorized actions and affected data.
- Search for related indicators.

## Eradication
- Remove malicious mailbox rules/persistence.
- Rotate compromised credentials/secrets.
- Remove malicious files or access.
- Patch relevant weaknesses.

## Recovery
- Restore account access after validation.
- Monitor for recurrence.
- Confirm normal business operation.

## Lessons Learned
Improve email filtering, phishing awareness, MFA coverage, identity monitoring, and detection rules.
