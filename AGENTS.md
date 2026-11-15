# The Citadel

> Agents Execute. Evidence Connects. Humans Govern.

## Purpose

The Citadel is a reference and knowledge repository for adopting the **Agentic Development Lifecycle (ADLC)** in real-world software engineering.

It provides reusable agents, skills, workflows, integration patterns, and governance practices that enable AI agents to collaborate with human teams throughout the Software Development Lifecycle.

The focus is **Tool-integrated ADLC** — extending existing tools such as Jira, Confluence, GitHub, and CI/CD rather than replacing them.

## Core Principles

- **Human-Governed:** Humans retain ownership of requirements, architecture, security, and release decisions.
- **Artifact-Driven:** Every stage produces traceable outcomes for subsequent stages.
- **Context-Aware:** Agents retrieve relevant information from authoritative sources.
- **Tool-Integrated:** Existing engineering tools remain the systems of record.
- **Reusable:** Agents, skills, and workflows should be portable across projects.
- **Pragmatic:** Prefer minimal, maintainable solutions over unnecessary complexity.

## Repository Organization

- `agents/` — Specialized agent roles and responsibilities.
- `skills/` — Reusable procedures and domain expertise.
- `workflows/` — ADLC lifecycle and agent handoff patterns.
- `integrations/` — MCP and external tool integration guidance.
- `governance/` — Quality gates, security, and human oversight.
- `examples/` — Practical implementation scenarios.

## Working Guidelines

1. Treat this repository as a reference toolkit, not a production application.
2. Follow existing conventions before introducing new structures.
3. Keep guidance concise, actionable, and technology-neutral where practical.
4. Clearly define inputs, outputs, dependencies, and approval gates.
5. Avoid duplicating artifacts already maintained in authoritative systems.
6. Never assume external integrations, permissions, or approvals exist.
