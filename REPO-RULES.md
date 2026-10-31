# Repo rules

## Markdown first

This repository shares **mostly markdown** (`.md`). That is the format agents and humans read as canon.

Allowed in-repo (v0.1):

- Markdown content (articles, concepts, sources, index)
- Small text sidecars if needed later (e.g. `.gitignore`, `LICENSE`, `VERSION.md`)
- Optional: mermaid diagrams **inside** markdown (no image export required)

## Media stays out of this repo

Do **not** commit generated or binary media here: PNG, JPG, SVG logos, hero images, video, audio, fonts, large zip dumps.

Share media another way:

1. **Preferred (current):** Samba share on DimSum's box — `\\100.113.55.47\agentOS\media` (Tailscale), sibling to the wiki markdown under `agentOS/FDE-llm-wiki`
2. **TBD:** other object storage / CDN if we outgrow Samba

In markdown, link media with a short note of where the file lives (Samba path or future URL), not a git blob.

## Connections required

Every article/concept page should keep a `## Connections` section tying it to the brand thesis, audience, knowledge gaps, and related pages. See `concepts/kb-process.md`.

## Steward

DimSum maintains this KB. Version bumps are recorded in `VERSION.md`.

## Order routing vs AgentOS (2026-10-31 ~16:10 HKT; folders created 2026-10-31 ~18:15 HKT)

- Keyword **FDE** / **AI 前線部署** → this repo. Keyword **AgentOS** → private `llm-wiki` only. Never mix.
- Top-level `ideas/` and `workshop/<workstream>/` with **English kebab-case** workstream slugs (first: `grok-bot-social-media-automation`).
- AgentOS owns `projects/`, `fleet/`, `branding/`, `sources/` — do not recreate those trees here for fleet memory.
- Third-party captures in `sources/` (e.g. 創作邦) are **blueprints only** — not River branding for **AI 前線部署**.
- Canon: [concepts/order-wiki-routing.md](concepts/order-wiki-routing.md).
