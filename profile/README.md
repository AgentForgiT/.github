# AgentForge

**Open engineering resources for agentic AI systems.**

AgentForge is building the platform layer for agentic AI: a provider-neutral gateway, a context-validation CLI, and an open specification for project context that humans and AI tools both read.

## Repositories

| Repository | Purpose |
|---|---|
| [agentforge](https://github.com/AgentForgiT/agentforge) | **Canonical monorepo** — gateway, CLI, SDK, MCP surface, AICS spec, benchmarks, ADRs, standards (code + releases live here; 1.0.0) |
| [agentforge-docs-site](https://github.com/AgentForgiT/agentforge-docs-site) | Published documentation site (live: agentforgit.github.io/agentforge-docs-site) |
| [agentforge-handbook](https://github.com/AgentForgiT/agentforge-handbook) | The public handbook for agentic AI engineering |
| [agentforge-mcp](https://github.com/AgentForgiT/agentforge-mcp) | Companion reference for the MCP surface (canonical code in the monorepo) |
| [agentforge-benchmarks](https://github.com/AgentForgiT/agentforge-benchmarks) | Companion reference for the benchmark framework (canonical code in the monorepo) |
| [agentforge-integrations](https://github.com/AgentForgiT/agentforge-integrations) | Companion reference for IDE/CLI/provider integrations |
| [agentforge-workflows](https://github.com/AgentForgiT/agentforge-workflows) | Companion reference for agent-automation patterns |
| [agentforge-community](https://github.com/AgentForgiT/agentforge-community) | Companion index for community & governance |
| [.github](https://github.com/AgentForgiT/.github) | Org templates, governance, and reusable workflows |
| agentforge-gateway / agentforge-cli | Historical prototypes (superseded by the monorepo) |

## What is AICS?

The AI Context Specification defines a `.agentforge/` directory — plain Markdown describing a project's vision, architecture, decisions, and standards — readable by humans and validated by machines, so any AI tool can be pointed at a project and understand it. The AgentForge monorepo is its own first validation: the context passes AICS validation in CI on every push.

## Status

- **1.0.0 shipped** (2026-08-01) — API surface frozen; semver discipline from here (breaking changes require a minor bump and an ADR).
- 9 accepted DECs, 38 accepted ADRs, 371 tests green offline, AICS Level-3 validated in CI.
- Release train: every release attaches wheels + benchmark results via the tag-gated publish workflow.

## Governance

Decisions are recorded, not remembered: constitution → charter → ADRs → RFCs → standards → requirements → milestones. Every sprint ships as a documented release. Templates live in this repository.