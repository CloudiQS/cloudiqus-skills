---
name: vmware-angle
description: Deep playbook for the VMware/Broadcom migration angle — the strongest CloudiQS commercial trigger right now. Facts, messaging, objections, migration paths, and MAP funding model.
---

# VMware/Broadcom Angle Skill

## The Situation (facts to use)
- Broadcom acquired VMware in November 2023
- Immediately moved to subscription-only bundle licensing
- Most customers saw 2–5x licence cost increases at renewal
- Perpetual licences discontinued — no downgrade path
- VMware partners lost authorisation — support landscape fragmented

## The Conversation Opener
"When does your VMware contract renew? We're helping UK businesses move before renewal to avoid the new Broadcom pricing — and AWS MAP often funds the migration."

## Key Messages
1. "The migration pays for itself — you'll save more on VMware licences than the migration costs"
2. "AWS MAP credits cover the EC2, storage, and network costs during migration"
3. "We've done this before — we know the fastest path off VMware onto AWS"
4. "You can move at your own pace — pilot first, then full migration"

## Migration Paths (for technical conversations)
| From | To | Method | Timeline |
|------|----|--------|---------|
| VMware vSphere | EC2 | AWS MGN (lift & shift) | 4–12 weeks |
| VMware vSphere | EKS | Re-platform + containerise | 8–20 weeks |
| VMware NSX | AWS networking | VPC + Transit Gateway | Parallel to above |
| VMware vSAN | EBS / EFS / FSx | Storage migration | Part of MGN |
| VMware on-prem | VMC on AWS | Lift to VMC, then modernise | 2–4 weeks initial |

## Common Objections
| Objection | Response |
|-----------|---------|
| "We just renewed" | "Good — that gives us 1–3 years to plan the migration properly and get MAP funding" |
| "We're staying on VMware" | "What's your plan when support ends? We can help you evaluate the options." |
| "Migration is too risky" | "We run a pilot of 1–3 VMs first. You don't commit to the full migration until the pilot proves it works." |
| "We don't have budget" | "AWS MAP often funds the migration costs — let me check your eligibility" |

## Funding Model for VMware Migrations
- MAP: covers EC2, EBS, data transfer during migration period (up to $2M)
- WAFR: often included post-migration (£5–25K credits)
- Net result: customer often pays less than VMware renewal for the migration itself
