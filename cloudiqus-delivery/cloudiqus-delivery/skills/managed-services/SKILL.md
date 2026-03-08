---
name: managed-services
description: CloudiQS MSP service delivery rhythm — daily, weekly, monthly operations using MontyCloud DAY2. SLA definitions, escalation paths, and customer review cadence.
---

# Managed Services Skill

## Operational Backbone: MontyCloud DAY2
CloudiQS uses MontyCloud DAY2 as the MSP operational platform.
Capabilities: automated patching, cost governance, compliance monitoring, multi-account management.

## Daily Operations (automated via MontyCloud)
- Infrastructure health checks
- Cost anomaly monitoring
- Security alert triage
- Backup verification
- Patch compliance check

## Weekly Rhythm
| Day | Activity |
|-----|----------|
| Monday | Pipeline review + customer health review |
| Wednesday | Customer technical check-ins (rotating) |
| Friday | Incident review, next week prep |

## Monthly Rhythm
- Monthly Value Report per customer (FinOps + security + delivery)
- Customer review call (30 min)
- WAFR progress update if in scope
- Expansion review (any signals >£500/month saving?)
- SLA compliance report

## SLA Tiers
| Tier | Response Time | Resolution Target | Customers |
|------|--------------|------------------|-----------|
| P1 — Critical | 15 minutes | 4 hours | Production down |
| P2 — High | 1 hour | 8 hours | Major degradation |
| P3 — Medium | 4 hours | 2 business days | Non-critical issues |
| P4 — Low | Next business day | 5 business days | Requests, improvements |

## Escalation Path
P1/P2: On-call engineer → Delivery Lead → Steve (if unresolved >2h)
P3/P4: Ticket system → assigned engineer → weekly review
