---
name: wafr-run
description: Well-Architected Framework Review methodology. All 6 pillars, 5-business-day credit submission rule, credit value by scope, and Partner Portal checklist.
---

# WAFR Run Skill

## The 5-Day Rule
Submit to AWS Partner Portal within **5 business days** of review completion. Set calendar reminder the day the review is scheduled. Late = rejected, no appeal.

## 6 Pillars Summary
| Pillar | Top Findings |
|--------|-------------|
| Operational Excellence | No runbooks, manual deployments, no alerting |
| Security | Root active, overprivileged IAM, no GuardDuty |
| Reliability | Single-AZ RDS, untested backups, no DR plan |
| Performance Efficiency | Over-provisioned, no auto-scaling |
| Cost Optimisation | No tagging, no budgets, idle resources |
| Sustainability | x86 where Graviton would do, oversized |

## Review Phases
Phase 1 (D1-2): Discovery — Trusted Advisor, Compute Optimizer, Cost Explorer, interviews
Phase 2 (D3-4): Assessment — score each pillar, document findings with evidence
Phase 3 (D5): Remediation plan — prioritised, phased, effort estimates

## Credit Values
| Scope | Credit |
|-------|--------|
| 1–2 pillars | £5,000–£10,000 |
| 3–4 pillars | £10,000–£18,000 |
| All 6 pillars | £18,000–£25,000 |

## Output: 7 Sections
1. Executive Summary · 2. Pillar Scorecards · 3. Finding Detail · 4. Remediation Roadmap · 5. Quick Wins · 6. Commercial Opportunity · 7. Credit Claim Checklist
