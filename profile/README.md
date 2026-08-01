# AgentForge

**Open engineering resources for agentic AI systems.**

AgentForge is building the platform layer for agentic AI: a provider-neutral gateway, a context-validation CLI, and an open specification for project context that humans and AI tools both read.

## Repositories

| Repository | Purpose |
|---|---|
| [agentforge](https://github.com/AgentForgiT/agentforge) | Canonical monorepo: gateway, CLI, AICS spec, ADRs, standards |
| [agentforge-handbook](https://github.com/AgentForgiT/agentforge-handbook) | The public handbook for agentic AI engineering |
| [agentforge-docs-site](https://github.com/AgentForgiT/agentforge-docs-site) | Published reference documentation |
| [agentforge-community](https://github.com/AgentForgiT/agentforge-community) | RFCs, ADRs, and governance discussion |
| agentforge-gateway / agentforge-cli | Historical prototypes (superseded by the monorepo) |

## What is AICS?

The AI Context Specification defines a `.agentforge/` directory — plain Markdown describing a project's vision, architecture, decisions, and standards — readable by humans and validated by machines, so any AI tool can be pointed at a project and understand it. The AgentForge monorepo is its own first validation: the context passes AICS validation in CI on every push.

## Governance

Decisions are recorded, not remembered: constitution → charter → ADRs → RFCs → standards → requirements → milestones. Every sprint ships as a documented `Genesis-0.0.x` release. Templates live in this repository.
