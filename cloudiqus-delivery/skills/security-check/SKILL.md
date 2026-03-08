---
name: security-check
description: CloudiQS cloud security assessment framework. IAM audit, GuardDuty, Security Hub, encryption, network posture. Produces risk-rated findings and remediation plan.
---

# Security Check Skill

## Assessment Scope
**IAM & Identity**
- Root account: MFA enabled? Access keys? Last used?
- IAM users: MFA enforced? Least privilege? No shared credentials?
- IAM roles: overprivileged? Star actions? Cross-account trust?
- IAM Identity Center: configured or using legacy IAM users?

**Detection & Response**
- GuardDuty: enabled in all regions? Findings reviewed?
- Security Hub: enabled? Standards activated? Score?
- CloudTrail: enabled? S3 bucket protected? Log validation?
- Config: enabled? Rules active?

**Network**
- Security groups: port 22/3389 open to 0.0.0.0/0?
- VPC flow logs: enabled?
- WAF: in front of public-facing workloads?

**Data Protection**
- S3: public access blocked at account level?
- Encryption at rest: EBS, RDS, S3 encrypted?
- Encryption in transit: TLS enforced?
- Secrets: no hardcoded credentials in code or EC2 user data?

## Risk Rating
- 🔴 CRITICAL: root active, public S3, port 22 open globally, no GuardDuty
- 🟡 HIGH: no MFA, overprivileged roles, no Security Hub
- 🟢 MEDIUM: missing encryption, no flow logs, incomplete Config
- ⚪ LOW: best practice gaps, policy improvements

## Output
1. Executive risk summary (one paragraph, board-readable)
2. Critical findings (fix within 24 hours)
3. High findings (fix within 7 days)
4. Full findings table with risk, evidence, fix
5. Remediation SOW outline
