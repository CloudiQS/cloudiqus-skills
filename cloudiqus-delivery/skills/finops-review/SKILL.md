---
name: finops-review
description: FinOps review methodology for CloudiQS MSP customers. Monthly Value Report format, quick win tiers, expansion signal rules. All figures in GBP.
---

# FinOps Review Skill

## Maturity Stages
Inform → Optimise → Operate
Guide every customer through all three. MSP customers should reach Operate within 6 months.

## Quick Win Tiers
**Tier 1 — Week 1, zero risk:**
Rightsize over-provisioned EC2 · Delete unattached EBS · Remove idle load balancers · S3 Intelligent Tiering

**Tier 2 — Month 1:**
Savings Plans · RDS rightsizing · Data transfer optimisation · Spot for non-critical

**Tier 3 — Quarter:**
Reserved Instances (1–3yr) · Serverless where appropriate · Multi-account governance

## Monthly Value Report (8 sections)
1. Executive Summary — total spend, trend, net saving
2. Cost Breakdown — top 5 services, month-on-month
3. Anomalies — spikes >£100, root cause, status
4. Rightsizing — specific instances, recommended type, saving in £
5. Budget Status — each budget, utilisation %, OK/WARNING/BREACHED
6. Actions Taken — what CloudiQS did, money saved
7. Recommended Actions — prioritised by saving, effort, risk
8. Expansion Signal — if rightsizing saving >£500/month, flag for commercial

## Expansion Signal Rule
Saving >£500/month identified → flag AMBER → notify Oliver:
"Expansion opportunity: [customer], £[X]/month identifiable saving. Recommended: optimisation engagement."
