---
name: opportunity-chain
description: The CEO master workflow. Takes any new opportunity — 2 sentences or a full brief — and runs all 7 tracks simultaneously: qualify, fund, ACE, alliance, SOW type, Agentic AI fit, action plan. Produces a one-page opportunity brief with everything Steve needs to move.
---

# Opportunity Chain Skill

## What This Does
You paste in what you know about an opportunity — could be a name and sector, could be meeting notes, could be an email. This skill runs every relevant track simultaneously and produces a one-page brief that tells you exactly what to do.

## The 7 Tracks (run in parallel)

### Track 1 — PAIN Qualification
Score 0–100 across 5 dimensions.
Verdict: HOT (register ACE today) / WARM (qualify further) / NURTURE / DISQUALIFY

### Track 2 — Funding Stack
Check all 6 programmes: MAP · POC · WAFR · MDF · Activate · BOX
Output: total potential funding £/$ and immediate actions

### Track 3 — ACE Registration
Type: Migration / New Business / Expansion / GenAI
Urgency: register today / register before SOW / register before work starts
Flag: RED if work has started without ACE

### Track 4 — Alliance Motion
PDM action required? YES/NO
Co-sell flag? YES/NO
Executive briefing needed? YES/NO
MDF opportunity? YES/NO

### Track 5 — SOW Type
Which SOW type fits: Discovery / Migration / MSP / GenAI POC / Security / WAFR / Production Agent
Estimated value: £[gross] / £[net after funding]
Prerequisites gate: pass/fail with blockers listed

### Track 6 — Agentic AI Fit
Is there an Agent Bakery angle? YES/NO
If YES: which Quick Suite agent, or custom?
POC credits applicable? Estimated value?
Time to working agent: X weeks

### Track 7 — Action Plan
What YOU do today (Steve)
What OLIVER does today
What goes to PDM today
What the customer needs to know

## Output Format — The One-Page Opportunity Brief

```
OPPORTUNITY: [Customer Name]
Date: [today]
Source: [how it came in]

QUALIFICATION
Score: [X]/100 | Verdict: [HOT/WARM/NURTURE/DISQUALIFY]
Top signals: [1] [2] [3]
Gaps: [what's still unknown]

FUNDING STACK
MAP: [ELIGIBLE/NOT ELIGIBLE] — £[estimate] — Action: [what to do today]
POC: [ELIGIBLE/NOT ELIGIBLE] — $[estimate] — Action: [get PDM approval]
WAFR: [ELIGIBLE/NOT ELIGIBLE] — £[estimate] — Action: [schedule review]
Total potential funding: £[X]

ACE
Register as: [type]
Urgency: [TODAY / before SOW / before work starts]
[RED FLAG if work started]

ALLIANCE
PDM brief needed: [YES/NO] — [what to say]
Co-sell flag: [YES/NO]
MDF opportunity: [YES/NO]

SOW
Type: [SOW type]
Scope: [brief scope]
Gross value: £[X]
Net after funding: £[Y]
Prerequisites: [CLEAR / BLOCKED — list blockers]

AGENTIC AI FIT
Angle: [YES — which agent / NO]
Quick Suite or custom: [answer]
POC credits: [$ estimate]
Time to working agent: [X weeks]

ACTION PLAN
TODAY — Steve: [specific action]
TODAY — Oliver: [specific action]
TODAY — PDM: [specific action]
THIS WEEK: [what needs to happen before next Monday]
BEFORE SOW: [what must be resolved]
```
