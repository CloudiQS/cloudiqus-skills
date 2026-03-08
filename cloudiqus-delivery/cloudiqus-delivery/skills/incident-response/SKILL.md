---
name: incident-response
description: CloudiQS cloud security incident response — detection, containment, investigation, remediation, and post-incident review. Based on AWS security incident response best practices.
---

# Incident Response Skill

## Incident Severity
| Level | Example | Response |
|-------|---------|---------|
| P1 — Critical | Root compromise, data exfiltration, ransomware | All hands, Steve notified immediately |
| P2 — High | Unauthorised access, GuardDuty critical finding | Delivery lead + on-call engineer |
| P3 — Medium | Suspicious activity, policy violation | On-call engineer, next business hour |

## Response Phases

### 1. Detection & Triage (first 15 minutes)
- Confirm the incident is real (not false positive)
- Assess scope: which accounts, which resources, what data?
- Assign severity level
- Notify Steve if P1 or P2

### 2. Containment (first 1 hour for P1)
- Isolate compromised resources (security group, IAM deny policy)
- Revoke suspicious credentials immediately
- Snapshot affected resources before any changes
- Enable enhanced logging (CloudTrail, VPC flow logs, S3 access logs)

### 3. Investigation
- CloudTrail: who did what, when, from where?
- GuardDuty findings: attack pattern?
- IAM Access Analyzer: what was accessible?
- Timeline of events: reconstruct attacker actions

### 4. Remediation
- Remove access for compromised credentials
- Patch exploited vulnerability
- Harden affected configuration
- Verify no persistence mechanisms (new IAM users, Lambda backdoors, etc.)

### 5. Post-Incident Review (within 48 hours)
- Root cause confirmed
- Timeline documented
- Lessons learned
- Controls improved
- Customer report (if MSP customer affected)

## Former Employee Protocol (🔴 immediate)
If former employee had AWS access: disable IAM user, rotate all shared credentials, check CloudTrail for recent activity, report to Steve within 1 hour.
