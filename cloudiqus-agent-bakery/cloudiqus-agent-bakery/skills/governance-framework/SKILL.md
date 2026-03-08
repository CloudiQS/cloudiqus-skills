---
name: governance-framework
description: AI governance framework for CloudiQS Agent Bakery — aligned to Singapore Model AI Governance Framework and AWS Agentic AI Competency requirements. Used in competency applications and enterprise customer conversations.
---

# Governance Framework Skill

## Why This Matters
- AWS Agentic AI Competency requires demonstrated AI governance
- Enterprise customers (finance, healthcare) require it before deployment
- Singapore Model AI Governance Framework is the reference CloudiQS uses

## CloudiQS AI Governance Principles

### 1. Human Oversight
- GREEN/AMBER/RED autonomy model applied to all agents
- All AMBER actions require human approval before execution
- All agent actions are logged and auditable
- Override mechanism: humans can stop any agent action

### 2. Transparency
- Every agent output identifies it was AI-generated
- Reasoning is explainable — agent shows its work
- Confidence levels communicated where relevant
- Limitations documented for each agent

### 3. Data Governance
- No training on customer data without explicit consent
- Data stays in customer's AWS account
- Cross-account access is read-only and auditable
- PII handling: no PII stored in agent memory by default

### 4. Bias & Fairness
- Agents reviewed for biased outputs before production deployment
- Sensitive decisions (hiring, lending) explicitly excluded from autonomous action
- Customer-specific context overrides generic model assumptions

### 5. Accountability
- CloudiQS is accountable for agent design and deployment
- Customer is accountable for the business processes the agent runs
- SLA: agent performance monitored, degradation triggers review

## AWS Agentic AI Competency Alignment
- Governance documentation submitted as part of competency application
- Customer case studies demonstrate governance in production
- Technical controls: IAM least privilege, CloudTrail logging, GuardDuty on agent runtime
