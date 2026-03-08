---
name: agentcore-architecture
description: AWS Bedrock AgentCore technical architecture — runtime, gateway, memory, tools, A2A protocol, and FAST template. Reference for Agent Bakery delivery and technical conversations.
---

# AgentCore Architecture Skill

## What AgentCore Is
Amazon Bedrock AgentCore is AWS's managed runtime for production AI agents.
Announced at re:Invent 2024. CloudiQS is building on it from day one.

## Core Components

### AgentCore Runtime
- Runs your agent code as a container (Docker)
- Managed lifecycle — scales to zero, scales up on demand
- Authentication via Cognito
- Supports: Strands Agents, LangGraph, custom Python

### AgentCore Gateway
- Secure proxy between agent and external tools
- Lambda functions sit behind the Gateway
- Agent calls tools through Gateway — authenticated, logged, governed
- CloudiQS adds: Cost Explorer, Security Hub, ACE API tools

### AgentCore Memory
- Persistent memory across sessions
- Agent remembers context from prior conversations
- Per-user or shared memory

### A2A Protocol (Agent-to-Agent)
- Agents can call other agents
- CloudiQS Orchestrator calls FinOps, Security, SDR agents via A2A
- Each agent is a separate Runtime instance

## FAST Template
Foundation: `awslabs/fullstack-solution-template-for-agentcore`
What it gives you: React UI (Next.js) · Amplify hosting · Cognito auth · CDK infrastructure · Gateway Lambda tools

## Agent Build Stack
- Framework: Strands Agents (AWS-built, Python)
- Model: Claude Sonnet 4 (via Bedrock)
- Playbooks: loaded from vibe-context/ — the agent's domain knowledge
- Tools: Lambda functions for AWS APIs, external APIs, internal data

## Cost
- AgentCore Runtime: ~$0.016/hour serverless
- Claude Sonnet per interaction: ~$0.003
- Total for 20 MSP customers reviewed monthly: <$5/month
