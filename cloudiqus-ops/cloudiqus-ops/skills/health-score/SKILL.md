---
name: health-score
description: CloudiQS customer health scoring model (0–100). Tracks AWS spend, engagement, delivery, satisfaction, and renewal risk. Updates monthly. Triggers churn and expansion workflows.
---

# Customer Health Score Skill

## Scoring Model (0–100)

| Dimension | Weight | Green (full points) | Amber | Red (0 points) |
|-----------|--------|---------------------|-------|----------------|
| AWS Spend Trend | 25 | Increasing | Flat | Decreasing |
| Service Breadth | 20 | 3+ services | 2 services | 1 service |
| Stakeholder Engagement | 20 | Monthly touchpoint | Quarterly | No contact |
| Delivery Quality | 20 | No open issues | 1–2 issues | 3+ or P1 open |
| Satisfaction Signal | 15 | Positive feedback | Neutral | Complaint or churn signal |

**Total:**
- 75–100: 🟢 GREEN — healthy, look for expansion
- 50–74: 🟡 AMBER — at risk, intervention needed
- 25–49: 🔴 RED — high churn risk, escalate to Steve
- 0–24: ⛔ CRITICAL — emergency review

## Monthly Health Review
Run for every MSP customer by the 5th of each month.
Input: AWS spend data + delivery notes + stakeholder contact log
Output: Score + trend (UP/STABLE/DOWN) + recommended action

## Trigger Rules
- Score drops to AMBER: Oliver calls within 5 business days
- Score drops to RED: Steve involved within 2 business days
- Score improves to GREEN + expansion signal: flag to Oliver for commercial conversation
