# llm-wiki

**v0.1.2** · Living knowledge base for the brand · Steward: **DimSum**  
GitHub: [riverho/agentOS-FDE](https://github.com/riverho/agentOS-FDE) (public; older private copy: riverho/FDE-llm-wiki)  
Box path: `/workspace/agentOS/FDE-llm-wiki` · Samba: `\\100.113.55.47\agentOS\FDE-llm-wiki`  
(Moved from `agentOS/llm-wiki` on 2026-10-28; that path is now the internal fleet wiki.)

## Big idea (north star)

Help companies, one-person companies, and individuals **land their ideas successfully**.  
Audience: **SMB** and individuals who are hungry to learn or keen to turn ideas into action.  
We **fill gaps in their knowledge**.

→ [concepts/brand-thesis.md](concepts/brand-thesis.md)  
→ [concepts/kb-process.md](concepts/kb-process.md)  
→ [REPO-RULES.md](REPO-RULES.md) · [VERSION.md](VERSION.md)

## Share rule (v0.1)

- **In git:** mostly markdown.
- **Media (png, logo, …):** Samba `agentOS/media` (or TBD) — **not** this repo. See [REPO-RULES.md](REPO-RULES.md).


## Order routing (River DECISION 2026-10-31 ~16:10 HKT)

| Keyword | Goes to |
|---|---|
| **FDE** or **AI 前線部署** | **This** wiki (`riverho/agentOS-FDE`) |
| **AgentOS** | Private agent memory wiki (`/workspace/agentOS/llm-wiki`, `riverho/agentOS`) — **not** here |

Never mix. Future `ideas/` and `workshop/<workstream>/` (English kebab-case workstream slugs) belong **in this FDE wiki** when River approves creating them — not under AgentOS. AgentOS keeps `projects/` · `fleet/` · `branding/` · `sources/`. Details: [concepts/order-wiki-routing.md](concepts/order-wiki-routing.md).

Workshop business formal name: **AI 前線部署**. Biz / product: **FDE llm wiki** (this repo).

## Idea map (current)

```
Brand thesis (land ideas successfully)
├── Fill knowledge gaps ──► practical guides, playbooks, cases
├── Audience: SMB / learners / action-oriented individuals
└── Vehicle (example): Grok Bot guide
        ├── plans & start → reduces “is it worth it / how do I begin?” gap
        ├── multi-bot + routines → reduces “how do I operate alone?” gap
        ├── safe outbound / Auto-review → reduces “I dare not ship” gap
        └── Job-seeking pipeline (Scout + Courier) → multi-bot + Notion HITL + Gmail send
```

## Concepts

- [Brand thesis](concepts/brand-thesis.md)
- [How this KB works](concepts/kb-process.md)
- [Job-seeking pipeline (Scout + Courier)](concepts/job-seeking-pipeline.md)
- [Order keyword routing — FDE vs AgentOS](concepts/order-wiki-routing.md) (River DECISION 2026-10-31 ~16:10 HKT)

## Articles

1. [Grok Bot 怎麼開始用？超完整解析與案例分享](articles/grok-bot-guide.md) — [public](https://creatorhome.tw/articles/grok-bot-guide)

## Steward rule

DimSum keeps this wiki updated whenever content changes **and** whenever a new connection between ideas appears. Articles alone are not enough — the links are part of the product.
