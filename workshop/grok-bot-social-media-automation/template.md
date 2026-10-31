---
title: Shareable bot template — blueprint
workstream: grok-bot-social-media-automation
updated: 2026-10-31
---

# Template blueprint (not exported yet)

**Status:** Scaffold + blueprint only. **OPEN** — no Grok Bot share id / CreateBotShareJson / marketplace export in this pass. River does not yet have a bot to export for this workstream.

**Article is blueprint only.** River owns the eventual shareable template for **AI 前線部署**.

## What the shareable template should cover (from the article)

Derived from https://creatorhome.tw/articles/grok-bot-social-media-automation (郭政佑 Kevin · 創作邦 · published 2026-10-17 · updated 2026-10-23). Facts only.

### Roles (specialist split)

1. **統籌 / coordinator bot** — Receive social request; hand off to Social with: source, target platform + account, deliverable, full datetime, review boundary. Must not enqueue official publish, immediate post, or auto-replies without human confirm. If Mac dispatch is unavailable, deliver a copy-pasteable task — do not claim executed.
2. **Social bot** — Draft from Notion 靈感庫 into 短文庫; do not invent bio/stats/results; list questions when data missing; body paragraphs separated by a full-width space line (U+3000) per author's habit; deliver body, platforms, accounts, image order, episode, datetime, article link; after human confirms a named version, hand Mac executor **schedule-only** Metricool write; return schedule read-back; after go-live, confirm public posts.

*(River may later ship one shared template that encodes both roles, or two specialist shares — OPEN.)*

### Human-in-the-loop

- Explicit approval text naming Notion URL, version, platforms/accounts, final body, images/order, Asia/Taipei datetime, links.
- Approve = schedule in Metricool only — **not** immediate publish.
- Any change to body/image/account/time → back to human.

### Tool surface the template should assume (installer still connects)

- Grok Bot (Mac or cloud dispatch)
- Notion (靈感庫 + 短文庫)
- Metricool (IG / Threads / FB brand accounts)
- Mac Codex or Claude Code as executor (author's setup; not an official Grok Bot built-in)
- Human final review

### Routines implied

- Daily early scan (article example: 08:00 Asia/Taipei) for next-24h **approved + complete** drafts → Metricool ahead of publish time; late approvals → one-off re-schedule; never force immediate publish; report failures (expired time, Mac down, unreadable source).
- First Test run of any routine: **read-only** plan listing — no Notion/Metricool/Flow writes.
- Post-time check: Metricool status + native platform URLs; FB/Threads first comment / IG Flow scoped to that post.

### Onboarding the share should drive

See [onboarding.md](onboarding.md) — AI-guided checklist: **tools → flows → folders**, then work starts.

### Explicitly out of scope this pass

- Real bot profile / share JSON
- Copying third-party site branding into River assets
- Claiming official Grok Bot product features beyond what the article itself disclaims as personal setup

## OPEN fields (River)

| Field | Status |
|-------|--------|
| Share id / marketplace link | OPEN |
| Single vs dual-bot share | OPEN |
| Final River-owned role prompts (vs article examples) | OPEN |
| Which Mac executor / connectors are required vs optional | OPEN |
