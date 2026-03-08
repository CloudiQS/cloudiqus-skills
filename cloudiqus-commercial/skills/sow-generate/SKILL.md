---
name: sow-generate
description: Generate complete CloudiQS Statements of Work. 7 SOW types, 11 sections. Always runs prerequisites gate and funding check first. Uses [TBC] for missing fields — never asks questions, never leaves a section blank.
---

# SOW Generation Skill

## The Golden Rule
Never generate a SOW without completing the prerequisites gate. Funding missed after SOW is sent is permanent.

## Prerequisites Gate
- [ ] ACE registered?
- [ ] MAP eligibility confirmed or ruled out?
- [ ] POC/pilot PDM written approval if GenAI scope?
- [ ] WAFR scheduled if in scope?
- [ ] Pricing approved by Steve?
Any unchecked → flag AMBER, do not generate until resolved.

## 7 SOW Types
| Type | Value Range | Funding |
|------|-------------|---------|
| Discovery & Assessment | £5–15K | WAFR credits |
| Migration — Lift & Shift | £30–150K | MAP |
| Migration — Re-platform | £50–300K | MAP |
| MSP Onboarding | £10–25K + MRR | MDF possible |
| GenAI / Agent Bakery POC | £15–50K | POC up to $25K |
| Security Assessment | £10–40K | WAFR credits |
| Well-Architected Review | £5–25K | WAFR credits cover review |

## 11 SOW Sections
1. Executive Summary
2. Background & Context
3. Scope of Work (with explicit exclusions)
4. Deliverables (numbered, with acceptance criteria)
5. Approach & Methodology
6. Team (named resources and roles)
7. Timeline (week-by-week, milestones, dependencies)
8. Pricing (GBP, payment milestones, expenses)
9. AWS Funding (credits applied, customer obligations)
10. Assumptions & Dependencies
11. Terms (reference to MSA or standard CloudiQS T&Cs)

## Output Rules
- [TBC] for any missing field — never leave blank, never ask
- Deliverables must be specific and measurable
- Timeline in weeks — never "approximately X months"
- Always include AWS funding cover letter if MAP/POC applies
- AMBER action — draft for Steve/Oliver review before sending
