---
name: lessons-system
description: The CloudiQS self-correction system. Read at the start of every session. Append every correction immediately. The system gets smarter over time.
---

# Lessons System

## How It Works
- Read `lessons-system.md` at the start of every session
- After any correction, append immediately — do not wait
- Format: `[DATE] | [SKILL] | CONTEXT: what went wrong. RULE: specific fix. TRIGGER: when to apply.`
- If the same mistake recurs, the lesson was too vague — rewrite it more specifically

## Seed Lessons (inherited from session history)

[2026-03] | sow-generate | CONTEXT: SOW sent before checking MAP eligibility — funding missed. RULE: Always run funding-stack check before generating SOW. TRIGGER: Every SOW generation, no exceptions.

[2026-03] | wafr-credits | CONTEXT: WAFR credit submitted 7 days after review — rejected. RULE: Submit to Partner Portal within 5 business days. Set calendar reminder same day review is scheduled. TRIGGER: Every WAFR review scheduling.

[2026-03] | sdr-outreach | CONTEXT: Generic email sent with no company-specific detail — no reply. RULE: Every email must reference one specific thing about the target company. TRIGGER: Before sending any cold email.

[2026-03] | ace-lifecycle | CONTEXT: ACE registered after work started — MAP credit rejected. RULE: Register ACE before any billable work begins. TRIGGER: Opportunity reaches HOT (75+), or SOW is being prepared.

[2026-03] | pain-qualify | CONTEXT: SOW sent to unqualified lead — wasted 4 hours. RULE: Lead must score 50+ before any SOW work begins. TRIGGER: Any SOW request on unscored opportunity.

[2026-03] | finops-review | CONTEXT: Report showed USD figures — customer confused. RULE: All customer-facing figures in GBP. Use 0.79 conversion unless live rate given. TRIGGER: Every report generation.
