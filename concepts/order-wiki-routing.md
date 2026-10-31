---
title: Order wiki routing — FDE vs AgentOS
owner: DimSum
updated: 2026-10-31
tags: [decision, routing, fde, agentos, workshop]
---

# Order keyword routing — FDE LLM Wiki vs AgentOS

**DECISION 2026-10-31 ~16:10 HKT** · River (to DimSum) · Steward: DimSum

When River places an order, keywords choose which wiki receives the work. **Never mix** the two.

| Keyword | Wiki | Box | GitHub |
|---|---|---|---|
| **FDE** or **AI 前線部署** | **This** shared FDE LLM Wiki (Biz of workshop business **AI 前線部署**) | `/workspace/agentOS/FDE-llm-wiki` | `riverho/agentOS-FDE` |
| **AgentOS** | River's private agent memory wiki | `/workspace/agentOS/llm-wiki` | `riverho/agentOS` (private) |

## Structure (locked; first folders created 2026-10-31 ~18:15 HKT)

- **This repo (FDE)** owns top-level `ideas/` and `workshop/<workstream>/`.
- **Workstream slugs:** English **kebab-case**. First: `grok-bot-social-media-automation`.
- **AgentOS** keeps `projects/`, `fleet/`, `branding/`, `sources/` — not ideas/workshop trees.
- First workstream is scaffold + third-party article **blueprint** only; River owns the eventual shareable template for **AI 前線部署**. No live bot share export in the creating order.

Internal canon (full log): AgentOS `learnings/order-wiki-routing.md`. Naming: workshop business **AI 前線部署** · Biz **FDE llm wiki**.

## Connections

- **Brand thesis:** [[brand-thesis]] — this wiki is the Biz vehicle for landing ideas; routing keeps fleet memory separate.
- **KB process:** [[kb-process]]
- **Repo rules:** [../REPO-RULES.md](../REPO-RULES.md)

## Log

- 2026-10-31 ~16:10 HKT · River (to DimSum; Cantonese) · DECISION · Keywords **FDE** / **AI 前線部署** → this wiki; **AgentOS** → private llm-wiki; never mix. Lock: English kebab-case workstream slugs; future `ideas/` + `workshop/<workstream>/` here; AgentOS keeps projects/fleet/branding/sources; no folders created yet. (source: River → DimSum chat; wiki by DimSum executor)
