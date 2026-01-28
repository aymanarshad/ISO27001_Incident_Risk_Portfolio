# Incident Report – IR-2024-001

## Incident Summary
A phishing attack resulted in the compromise of an employee email account after credentials were submitted on a malicious website.

## Detection
- Source: SIEM alert
- Alert Type: Suspicious login from foreign IP
- Date/Time: 2024-10-12 14:32 UTC

## Impact
- One corporate email account compromised
- Potential unauthorized access to internal communications

## Containment & Recovery
- User password reset
- MFA enforced
- Active sessions terminated

## Root Cause
- Lack of phishing awareness
- MFA not enforced on email system

## Incident Status
Closed
