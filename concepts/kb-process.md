---
title: How this KB works
owner: DimSum
updated: 2026-10-24
tags: [kb, llm-wiki, connections, process]
---

# How this KB works

`llm-wiki` is the **living knowledge base** for the brand. It is not a dump of articles.

## Always keep

1. **Canon pages** — articles and concepts we stand behind.
2. **Connections between ideas** — explicit links: what enables what, what fills which gap, what audience each piece serves.
3. **Freshness** — when a public post updates, or a new idea lands, update the wiki *and* the connection graph, not only the file.

## Connection rules

When ingesting or editing, always answer:

- **Serves which audience?** (SMB / learner / action-oriented individual)
- **Fills which knowledge gap?** (e.g. pricing, multi-bot design, safe outbound)
- **Connects to which other pages?** (upstream prerequisites, downstream next steps, related cases)
- **Supports the big idea how?** (land idea → knowledge → action)

Prefer a short `## Connections` section at the bottom of every article/concept page.

## Layout

| Path | Role |
|------|------|
| `README.md` | Index + map |
| `concepts/` | Brand thesis, audience, recurring ideas |
| `articles/` | Published or draft pieces (canon copies) |
| `sources/` | Original URLs and metadata (third-party; not River brand) |
| `ideas/` | Idea incubation (English kebab-case) |
| `workshop/` | Workstreams: folder + bot-template blueprint |

## Steward habit

DimSum updates this folder whenever brand content is created, revised, or a new link between ideas becomes clear — without waiting to be asked.
