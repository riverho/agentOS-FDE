---
title: Source — 如何用 Grok Bot 協助自動化經營社群
captured: 2026-10-31
tags: [source, third-party, creatorhome, grok-bot, social-media]
---

# Source: 如何用 Grok Bot 協助自動化經營社群

- **URL:** https://creatorhome.tw/articles/grok-bot-social-media-automation
- **Site:** 創作邦 (creatorhome.tw) — **third-party**; not River / **AI 前線部署** / **FDE llm wiki** branding
- **Author:** 郭政佑 Kevin
- **Published:** 2026-10-17
- **Content updated:** 2026-10-23
- **Ingested into FDE wiki:** 2026-10-31 ~18:15 HKT (Asia/Hong_Kong)
- **Hero / cover (third-party CDN):** article cover image hosted on zd85ekg7.us-west.insforge.app (see live page)
- **Related idea:** [../ideas/grok-bot-social-media-automation/](../ideas/grok-bot-social-media-automation/)
- **Related workshop:** [../workshop/grok-bot-social-media-automation/](../workshop/grok-bot-social-media-automation/)

Canonical reader-facing page is the URL above. This file is a **third-party capture** for agents: metadata + facts taken from the page only. Use as a **blueprint** for a River-owned Grok Bot template under **AI 前線部署** — do **not** treat 創作邦 / creatorhome / the author as River branding.

## Third-party notice (River / fleet — 2026-10-31)

**創作邦** (creatorhome.tw) and this article's author are **third-party**. Cite as source only. River owns the eventual shareable bot template for **AI 前線部署** / **FDE llm wiki**.

## Page one-liner (from the article)

作者用統籌 Bot 派工、Social Bot 起草，讓 Mac 上的 Codex／Claude Code 執行，再用 Notion 管稿、Metricool 排程 IG／Threads／FB；文章從建立 Bot、準備稿件、本人審核，到提前掃描與發布確認，帶讀者走完第一篇貼文。

## Disclaimer on the page (fact)

The author states this is their own setup, not official Grok Bot features, and results are not guaranteed. Field names, approval phrases, and schedules in the article are examples for trying the flow — not an install-time default and not a verbatim backup of the author's live config.

## Tools named on the page

| Tool | Role (per article) |
|------|--------------------|
| Grok Bot | 統籌 Bot (personal assistant) takes requests and dispatches; Social Bot drafts and plans scheduling |
| Mac Codex / Claude Code | After dispatch, actually reads data, prepares copy, and operates tools; in this setup Grok Bot only dispatches |
| Notion | 靈感庫 + 短文庫; practice post keeps copy, assets, time, and review notes in one record |
| Metricool | Schedules Instagram, Threads, and Facebook; publishes when the scheduled time arrives |
| Human (author) | Chooses topics, confirms content; before publish checks episode/count, images, and timing to avoid collisions |

First round suggestion on the page: one platform, one short post, one image the user has rights to use; expand platforms/series after the path works.

## Steps summarized (facts from the page)

1. **Install / sign-in** — Grok Bot Mac app; Notion + Metricool signed in; Metricool brand/accounts linked; Codex or Claude Code signed in separately.
2. **Create two bots** — 統籌 (personal assistant) + Social; sample role descriptions for dispatch vs draft/schedule boundaries (no publish without human confirm).
3. **Read-only connectivity test** — Notion 靈感庫/短文庫 URLs + Metricool target account; executor reports env, DB fields, test row; no writes.
4. **Prepare one Notion draft** — minimal fields (title, source, body/version, platform/account, images/episode, scheduled time Asia/Taipei, article link, review + result logs); draft via Social, stop at 待審.
5. **Human approve** — explicit approval naming version, platforms, body, images, time, links; schedule only, never immediate publish.
6. **Metricool schedule** — per-platform link handling (FB first comment; Threads often manual first comment; IG Flow scoped to that post); re-open items to confirm schedule.
7. **Daily scan earlier than publish** — example 08:00 Asia/Taipei scan for next-24h approved complete drafts → Metricool ahead of e.g. 18:00 publish; late approvals get a one-off re-schedule, not silent wait / not force immediate publish. Mac must be available for Mac-side work.
8. **Confirm live posts** — Metricool status ≠ proof of public post; check native IG/Threads/FB; store URLs/results in Notion.
9. **Capture the working flow as a skill** — then grow; human still owns topics and final review.

## Sample prompts on the page (presence only)

The article includes example prompt blocks for: assistant role, Social role, read-only test, draft-from-inspiration, human approval, daily scan routine, and post-publish check. Treat as **examples** from the third-party page, not River canon or official Grok Bot defaults.

## Connections

- Idea: [../ideas/grok-bot-social-media-automation/](../ideas/grok-bot-social-media-automation/)
- Workshop workstream: [../workshop/grok-bot-social-media-automation/](../workshop/grok-bot-social-media-automation/)
- Related prior source (different article): [creatorhome-grok-bot-guide.md](creatorhome-grok-bot-guide.md)
- Brand thesis: [../concepts/brand-thesis.md](../concepts/brand-thesis.md) — fills “how do I operate social alone with bots?” gap for SMB / individuals
