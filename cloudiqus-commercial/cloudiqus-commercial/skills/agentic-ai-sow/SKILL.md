---
name: agentic-ai-sow
description: Specific SOW template for CloudiQS Agentic AI engagements — Agent Bakery POC, production deployment, and multi-agent platform. Includes AWS AgentCore architecture section, governance framework, and POC credit funding model. Never asks questions — uses [TBC] for missing fields.
---

# Agentic AI SOW Skill

## Always Load First
Load `north-star`, `sow-generate`, `poc-approval`, `agentcore-architecture`, `governance-framework`

## The Three Agentic AI SOW Types

### Type 1 — Agent Discovery & Design (£5–10K)
What: process analysis, agent design, data source mapping, build vs buy recommendation
Deliverable: Agent Design Document — process map, agent architecture, integration spec, success criteria, build plan
When: customer has AI ambition but hasn't scoped the use case yet
Funding: no specific funding — use as door-opener, leads to Type 2

### Type 2 — Agent POC (£15–50K gross, £0–25K net after POC credits)
What: working agent deployed in customer's AWS environment
Deliverable: production-grade agent running on AgentCore, validated against success criteria
When: use case defined, customer wants proof before full commitment
Funding: POC credits up to $25K (PDM written approval required before SOW sent)
Timeline: 4–6 weeks

### Type 3 — Production Deployment + Management (£30–150K build + £500–3,000/month)
What: full production deployment, Unify Portal, monitoring, ongoing management
Deliverable: live agent(s) in production, CloudiQS managing and improving
When: POC succeeded, customer ready to scale
Funding: MAP if replacing legacy infrastructure; WAFR credits if architecture review included

## The Agentic AI SOW — 13 Sections

Standard 11 sections PLUS:

**Section 12 — Agent Architecture**
- Agent type (Quick Suite or custom)
- AWS services: Bedrock AgentCore, Strands Agents, Lambda tools, Cognito, CloudFront
- Data sources and integration points
- Memory: session or persistent
- A2A: single agent or multi-agent
- Deployment: container on AgentCore Runtime

**Section 13 — AI Governance**
- Autonomy level: GREEN/AMBER/RED classification per action type
- Human oversight: what requires approval vs autonomous
- Audit trail: all actions logged to CloudTrail
- Data handling: PII policy, retention, access controls
- Compliance alignment: Singapore Model AI Governance Framework
- Override mechanism: how humans stop or redirect the agent

## Pricing Presentation for Agentic AI
Always show three lines:
```
Gross engagement value:     £[X]
AWS POC credit applied:    -£[Y]  (subject to PDM approval)
Net customer investment:    £[Z]
Monthly management fee:     £[M]/month
Year 1 total:               £[Z + 12M]
```

## The Business Case Section (always include)
```
Current process cost:        £[X]/month ([hours] × [rate])
Agent management cost:       £[M]/month
Net monthly saving:          £[X - M]/month
Payback period:              [Z / (X-M)] months
Year 1 net benefit:          £[(X-M)×12 - Z]
```

## Prerequisites Gate (Agentic AI specific)
- [ ] Use case scoped and agreed
- [ ] Data sources accessible and confirmed
- [ ] AWS account with Bedrock enabled in target region
- [ ] PDM written POC credit approval (before SOW sent — AMBER until confirmed)
- [ ] Governance requirements understood (regulated sector?)
- [ ] Success criteria agreed
- [ ] Steve has reviewed architecture
