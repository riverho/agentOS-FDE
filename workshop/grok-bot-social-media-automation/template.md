---
title: Shareable bot template — Social Media Automation
workstream: grok-bot-social-media-automation
updated: 2026-10-31
---

# Template — Social Media Automation (v2 staged unpublished)

**Status:** **v2 staged** unpublished via **CreateBotShareJson** (2026-10-31 ~18:54–18:55 HKT Asia/Hong_Kong). Display name: **Social Media Automation** · **version 2**. Design includes branding folders, HITL (gen assets / visual design / applications), optional research ask, Notion paired sample, branding-pass gate. Prior **v1** staged ~18:35 HKT. Workstream: `grok-bot-social-media-automation`.

**Not public yet** — awaits **River** confirm on the **v2** review card (re-stage is **done**; not awaiting another CreateBotShareJson). Marketplace / public link remains **awaiting River publish confirm**.

**Article is blueprint only.** River owns the shareable template for **AI 前線部署**. Third-party: 創作邦 / creatorhome (郭政佑 Kevin).

## River design notes (2026-10-31 · owner)

### ~18:35 HKT (pt210u) — worker + Metricool

1. **Worker stays flexible** — Ask the owner which worker to use. Default expectation: **Grok Bot worker**. Do not hard-lock Mac Codex / Claude Code; clarify choice during onboarding.
2. **Metricool is fixed** — Do **not** offer many scheduler choices (no Buffer / Later / native-only menus). Template focus is **automation** through Metricool.
3. Keep the full actual template content aligned with that automation loop (draft → human approve → Metricool schedule-only → confirm public).

### ~18:53 HKT (pt211u) — branding, content planning, HITL, research ask

1. **Branding + content planning** — Onboarding and workspace must include branding and a light content-planning habit (not only tools/schedulers).
2. **Workspace folders** — Establish **branding/**, **assets/**, **tone-and-voice/** (markdown + pointers; media out of git).
3. **Gate branding pass first**, then ensure **branding consistency** before volume posting. Third-party article brands ≠ owner brand.
4. **HITL (confirming party):** gen assets · visual design · applications approval.
5. **Notion sample:** short-post write-up with **image/video paired** in Notion.
6. **News / research:** Involve the process, but research is **not** mandatory. Onboarding **must still ask** (even though the template is social media) and save the choice.

## What the shareable template covers (from article + River notes)

### Roles (specialist split)

1. **統籌 / coordinator bot** — Receive social request; hand off to Social with: source, target platform + account, deliverable, full datetime, review boundary. Must not enqueue official publish, immediate post, or auto-replies without human confirm. If the chosen worker is unavailable, deliver a copy-pasteable task — do not claim executed.
2. **Social bot** — Draft from Notion 靈感庫 into 短文庫; do not invent bio/stats/results; list questions when data missing; body paragraphs separated by a full-width space line (U+3000) when matching author habit; deliver body, platforms, accounts, image order, episode, datetime, article link; after human confirms a named version, hand the **chosen worker** a **schedule-only** Metricool write; return schedule read-back; after go-live, confirm public posts. Respect branding stubs and consistency after branding pass.

*(Single vs dual-bot packaging still OPEN for River product choice; staged share is one Bot template named Social Media Automation, now v2.)*

### Human-in-the-loop

- Explicit approval text naming Notion URL, version, platforms/accounts, final body, images/order, timezone datetime, links.
- Approve = schedule in Metricool only — **not** immediate publish.
- Any change to body/image/account/time → back to human.
- **Confirming party also HITL-approves:** gen assets · visual design · applications (apps/accounts/Metricool brand use).
- **Branding pass** before volume posting.

### Branding & content planning

- Workspace: [branding/](branding/) · [assets/](assets/) · [tone-and-voice/](tone-and-voice/)
- Light content-planning habit (themes → 靈感庫); optional news/research intake **only if** owner said Yes.

### Tool surface

- Grok Bot (installer / owner account)
- Notion (靈感庫 + 短文庫; sample paired post with image/video)
- **Metricool only** for scheduling (IG / Threads / FB brand accounts)
- **Worker (ask owner):** Grok Bot worker (likely default) · Mac Codex · Mac Claude Code · or Manual copy-paste briefs
- Human final review (+ branding / gen-assets / visual / applications HITL)

### Routines implied

- Daily early scan (example 08:00 in owner timezone) for next-24h **approved + complete** drafts → Metricool ahead of publish time; late approvals → one-off re-schedule; never force immediate publish; report failures (expired time, worker down, unreadable source).
- First Test run of any routine: **read-only** plan listing — no Notion/Metricool/Flow writes.
- Post-time check: Metricool status + native platform URLs; FB/Threads first comment / IG Flow scoped to that post.
- Optional news/research → 靈感庫 when owner opted in.

### Onboarding the share should drive

See [onboarding.md](onboarding.md) — AI-guided checklist: **tools → branding gate / research ask / light planning → flows → folders**, then work starts. Worker choice + Metricool-fixed remain required.

### Explicitly out of scope

- Treating Metricool “scheduled” alone as “public confirmed”
- Offering alternate schedulers in the template UX
- Claiming third-party site branding as **AI 前線部署** / owner brand
- Volume posting before branding pass
- Mandating research when owner declined (still must **ask**)
- Going public before River confirm on the **v2** review card

## Fields (River)

| Field | Status |
|-------|--------|
| CreateBotShareJson / staged v1 **Social Media Automation** | **Done** (2026-10-31 ~18:35 HKT) — superseded by v2 stage for review |
| CreateBotShareJson / staged **v2** (branding/HITL/research-ask + skills) | **Done** (2026-10-31 ~18:54–18:55 HKT) — unpublished until River confirm on **v2** review card |
| Public / marketplace link | Awaiting River publish confirm on v2 |
| Single vs dual-bot share packaging | OPEN |
| Final River-owned role prompts (vs article examples) | OPEN (v2 staged; refine as needed) |
| Worker choice (Grok Bot worker likely) | **Design locked** — ask owner; keep flexible |
| Scheduler | **Design locked** — Metricool only |
| Branding workspace + pass gate | **Design locked** (2026-10-31 ~18:53 HKT) — stubs OPEN for owner fill |
| News/research | **Design locked** — ask; optional; save choice |
| HITL: gen assets / visual design / applications | **Design locked** — confirming party |
| Notion sample paired post (write-up + image/video) | **Design locked** — create in onboarding |
