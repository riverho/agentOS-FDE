---
title: Shareable bot template — Social Media Automation
workstream: grok-bot-social-media-automation
updated: 2026-10-31
---

# Template — Social Media Automation (v1 staged)

**Status:** **Staged** unpublished public Bot template via **CreateBotShareJson** (2026-10-31 ~18:35 HKT Asia/Hong_Kong). Display name: **Social Media Automation** · **version 1**. Workstream: `grok-bot-social-media-automation`.

**Not public yet** — awaits **River** confirm on the review card before publish. Share OPEN for *export* is **closed** (staged); marketplace / public link remains **awaiting River publish confirm**.

**Article is blueprint only.** River owns the shareable template for **AI 前線部署**. Third-party: 創作邦 / creatorhome (郭政佑 Kevin).

## River design notes (2026-10-31 · owner)

From River on the live template (~18:35 HKT / pt210u):

1. **Worker stays flexible** — Ask the owner which worker to use. Default expectation: **Grok Bot worker**. Do not hard-lock Mac Codex / Claude Code; clarify choice during onboarding.
2. **Metricool is fixed** — Do **not** offer many scheduler choices (no Buffer / Later / native-only menus). Template focus is **automation** through Metricool.
3. Keep the full actual template content aligned with that automation loop (draft → human approve → Metricool schedule-only → confirm public).

## What the shareable template covers (from article + River notes)

### Roles (specialist split)

1. **統籌 / coordinator bot** — Receive social request; hand off to Social with: source, target platform + account, deliverable, full datetime, review boundary. Must not enqueue official publish, immediate post, or auto-replies without human confirm. If the chosen worker is unavailable, deliver a copy-pasteable task — do not claim executed.
2. **Social bot** — Draft from Notion 靈感庫 into 短文庫; do not invent bio/stats/results; list questions when data missing; body paragraphs separated by a full-width space line (U+3000) when matching author habit; deliver body, platforms, accounts, image order, episode, datetime, article link; after human confirms a named version, hand the **chosen worker** a **schedule-only** Metricool write; return schedule read-back; after go-live, confirm public posts.

*(Single vs dual-bot packaging still OPEN for River product choice; v1 share is one Bot template named Social Media Automation.)*

### Human-in-the-loop

- Explicit approval text naming Notion URL, version, platforms/accounts, final body, images/order, timezone datetime, links.
- Approve = schedule in Metricool only — **not** immediate publish.
- Any change to body/image/account/time → back to human.

### Tool surface

- Grok Bot (installer / owner account)
- Notion (靈感庫 + 短文庫)
- **Metricool only** for scheduling (IG / Threads / FB brand accounts)
- **Worker (ask owner):** Grok Bot worker (likely default) · Mac Codex · Mac Claude Code · or Manual copy-paste briefs
- Human final review

### Routines implied

- Daily early scan (example 08:00 in owner timezone) for next-24h **approved + complete** drafts → Metricool ahead of publish time; late approvals → one-off re-schedule; never force immediate publish; report failures (expired time, worker down, unreadable source).
- First Test run of any routine: **read-only** plan listing — no Notion/Metricool/Flow writes.
- Post-time check: Metricool status + native platform URLs; FB/Threads first comment / IG Flow scoped to that post.

### Onboarding the share should drive

See [onboarding.md](onboarding.md) — AI-guided checklist: **tools → flows → folders**, then work starts. Worker choice + Metricool-fixed are required.

### Explicitly out of scope

- Treating Metricool “scheduled” alone as “public confirmed”
- Offering alternate schedulers in the template UX
- Claiming third-party site branding as **AI 前線部署**
- Going public before River confirm on the review card

## Fields (River)

| Field | Status |
|-------|--------|
| CreateBotShareJson / staged v1 **Social Media Automation** | **Done** (2026-10-31 ~18:35 HKT) — unpublished until River confirm |
| Public / marketplace link | Awaiting River publish confirm |
| Single vs dual-bot share packaging | OPEN |
| Final River-owned role prompts (vs article examples) | OPEN (v1 staged; refine as needed) |
| Worker choice (Grok Bot worker likely) | **Design locked** — ask owner; keep flexible |
| Scheduler | **Design locked** — Metricool only |
