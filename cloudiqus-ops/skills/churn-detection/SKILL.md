---
name: churn-detection
description: CloudiQS churn detection — early warning signals, churn risk scoring, intervention playbook, and win-back sequences for churned customers.
---

# Churn Detection Skill

## Early Warning Signals

### 🔴 High Risk (escalate within 48 hours)
- AWS spend decreasing >20% month-on-month
- Customer stops responding to comms
- P1 incident unresolved >48 hours
- Sponsor leaves the company
- "We're reconsidering our cloud partner" mentioned

### 🟡 Medium Risk (intervene within 1 week)
- Health score drops from GREEN to AMBER
- Reduced engagement at QBR
- Billing query raised (unusual)
- Competitor engagement detected
- 2+ support tickets open simultaneously

### 🟢 Monitor Closely
- Single negative feedback comment
- Delayed payment
- Headcount reduction at customer
- New CTO or IT Director appointed

## Intervention Playbook
1. **Detect:** monthly health score review catches early signals
2. **Triage:** Oliver reviews — medium risk or high risk?
3. **Act:**
   - Medium: Oliver proactive call within 5 days, QBR brought forward
   - High: Steve personal call within 48 hours, rescue plan prepared
4. **Address root cause:** delivery issue? value perception? commercial?
5. **Document:** log in customer context file, update health score

## Win-Back (post-churn)
Wait 90 days. Then:
Touch 1: "We've made changes since you left — here's what's new"
Touch 2: Relevant sector news or AWS funding they might have missed
Touch 3: Invitation to event or briefing (no direct sales pitch)
