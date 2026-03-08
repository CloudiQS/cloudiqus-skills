---
name: migration-plan
description: Cloud migration planning — 6R framework, VMware/Broadcom angle, phased approach, MAP funding model, TCO comparison. Always checks MAP eligibility.
---

# Migration Plan Skill

## The 6R Framework
| R | When | AWS Services |
|---|------|-------------|
| Rehost | Fast exit, low risk | AWS MGN |
| Replatform | Small optimisations alongside move | RDS, ECS/EKS |
| Repurchase | SaaS equivalent exists | N/A |
| Refactor | Strategic apps, worth investment | Lambda, EKS, Aurora |
| Retain | Regulatory, latency, cost reasons | N/A |
| Retire | Unused or redundant | N/A |

## Migration Phases
1. Discovery & Assessment (2–4 weeks): inventory, dependency mapping, 6R classification, TCO, MAP check
2. Foundation (2–4 weeks): Landing Zone, networking, security baseline, tagging
3. Pilot (2–4 weeks): 1–3 non-critical workloads, validate tooling and runbooks
4. Wave Migrations (4–16 weeks): grouped by dependency, 48-hour rollback window per cutover
5. Optimise & Handover: FinOps review, performance tuning, MSP transition

## TCO Comparison Template
| Cost Category | On-Premises | AWS (Year 1) | AWS (Year 3) |
|--------------|-------------|-------------|-------------|
| Infrastructure | £X | £Y | £Z |
| Licensing (VMware) | £X | £0 | £0 |
| Operations | £X | £Y | £Y |
| **Total** | **£X** | **£Y** | **£Z** |

## Output
1. 6R classification table · 2. Phased plan with timeline · 3. MAP funding model · 4. TCO comparison (3-year) · 5. Risk register (top 5) · 6. Phase 1 Discovery SOW outline
