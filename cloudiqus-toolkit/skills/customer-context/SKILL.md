---
name: customer-context
description: Template for per-customer context files. Create one per MSP customer. Loaded when working on that customer to give AI assistants full account knowledge without re-explaining every session.
---

# Customer Context Template

## How to Use
Create a file: `CUSTOMER_[NAME].md` in the cloudiqus-toolkit/skills/ folder.
Load it alongside north-star when working on that customer.

## Template

```markdown
---
name: customer-[name]
description: Context for [Customer Name] — AWS account, contract, contacts, services, renewal
---

# Customer: [Name]

## Account Details
- AWS Account ID: [ID]
- AWS Region(s): [regions]
- Monthly AWS Spend: £[amount]
- Contract Value: £[monthly] MRR / £[annual] ARR
- Contract Start: [date]
- Contract Renewal: [date]
- Notice Period: [days] days

## Contacts
- Technical: [name, title, email]
- Commercial: [name, title, email]
- Finance: [name, title, email]

## CloudiQS Services Delivered
- [service]: [brief description]

## Current Health
- Score: [0-100] / Trend: [UP/STABLE/DOWN]
- Last review: [date]
- Open issues: [list]

## Expansion Opportunities
- [opportunity]: [value estimate]

## Notes
[anything else relevant]
```

## Live Example: Voly
- AWS Account ID: [TBC — request from customer]
- Monthly Spend: ~£4,000 (estimated)
- Contract: £5,000/month retainer
- Services: AWS setup, Bedrock enablement, AI roadmap, consolidated billing
- Renewal: [TBC]
- Contacts: [TBC]
- Health: Green
