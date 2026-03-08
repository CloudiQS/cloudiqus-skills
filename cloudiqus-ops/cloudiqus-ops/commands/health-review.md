---
description: Run monthly health score review for all CloudiQS MSP customers. Flags amber/red and triggers appropriate actions.
argument-hint: "[customer name for single review, or 'all' for full portfolio]"
---
Load skills: `north-star`, `health-score`, `churn-detection`, `renewal-playbook`
Score each customer across 5 dimensions. Produce health dashboard. Flag any amber/red with recommended intervention. Identify expansion signals on green customers.
