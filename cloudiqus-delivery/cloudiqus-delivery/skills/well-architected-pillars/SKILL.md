---
name: well-architected-pillars
description: Reference guide to all 6 AWS Well-Architected Framework pillars — key principles, design questions, and CloudiQS-specific recommendations for each.
---

# Well-Architected Pillars Reference

## 1. Operational Excellence
Key principles: IaC, small reversible changes, anticipate failure, learn from operations
CloudiQS focus: runbooks, alerting, deployment automation, observability (CloudWatch, X-Ray)

## 2. Security
Key principles: strong identity, enable traceability, apply security at all layers, protect data in transit and at rest, keep people away from data, prepare for security events
CloudiQS focus: IAM Identity Center, GuardDuty, Security Hub, encryption everywhere, least privilege

## 3. Reliability
Key principles: automatically recover from failure, test recovery procedures, scale horizontally, stop guessing capacity, manage change in automation
CloudiQS focus: Multi-AZ, auto-scaling, tested backups, DR plan, fault isolation

## 4. Performance Efficiency
Key principles: use advanced technologies as a service, go global in minutes, use serverless, experiment more often, consider mechanical sympathy
CloudiQS focus: right instance type, Graviton where possible, managed services over self-managed

## 5. Cost Optimisation
Key principles: implement cloud financial management, adopt a consumption model, measure overall efficiency, stop spending money on undifferentiated heavy lifting, analyse and attribute expenditure
CloudiQS focus: tagging governance, budgets + alerts, rightsizing, Savings Plans, FinOps reporting

## 6. Sustainability
Key principles: understand your impact, establish sustainability goals, maximise utilisation, anticipate and adopt new hardware and software offerings, use managed services, reduce downstream impact
CloudiQS focus: Graviton instances, right-sizing, serverless, efficient architecture patterns
