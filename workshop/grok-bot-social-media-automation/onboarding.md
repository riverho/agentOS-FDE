---
title: Onboarding checklist — Social Media Automation
workstream: grok-bot-social-media-automation
updated: 2026-10-31
---

# Onboarding checklist

Order locked by River (2026-10-31 ~15:28 HKT): **tools → flows → folders**, then work starts.  
River design 2026-10-31 ~18:53 HKT: insert **branding workspace + branding-pass HITL gate** after tools (before volume flows); ask **news/research** preference (optional, not mandatory); light **content planning**; HITL for gen assets / visual design / applications approval; Notion sample short-post paired with image/video.

Aligned with staged template **Social Media Automation** **v2** (CreateBotShareJson 2026-10-31 ~18:54–18:55 HKT; branding / HITL / research-ask) — awaiting River confirm on v2 review card. Prior v1 ~18:35 HKT. River design notes also: **ask worker choice** (likely Grok Bot worker); **Metricool fixed**.

Blueprint (facts only): https://creatorhome.tw/articles/grok-bot-social-media-automation

## 1. Tools (install / sign-in / connect)

- [ ] Grok Bot installed and signed in
- [ ] Notion signed in; can open intended databases (靈感庫 + 短文庫) — create minimal DBs if missing
- [ ] **Metricool** signed in; brand linked to the IG / Threads / FB accounts that will publish (verify names/handles, not just avatars). **Do not** pitch Buffer, Later, or other schedulers
- [ ] **Worker choice (required — ask owner):** Grok Bot worker (recommended default) · Mac Codex · Mac Claude Code · Manual (copy-pasteable briefs only). Save to profile memory. If Mac options need a machine online, say so when relevant
- [ ] Timezone for schedules chosen (e.g. Asia/Hong_Kong or Asia/Taipei)
- [ ] First-round scope chosen: one platform, one short post, one rights-cleared image

## 1b. Branding workspace + branding-pass gate (after tools; before volume flows)

See [branding/index.md](branding/index.md) · [folders.md](folders.md).

- [ ] Create / confirm workspace folders: **branding/**, **assets/**, **tone-and-voice/** (markdown stubs + media pointers; no binaries in git)
- [ ] Walk stubs: tone-and-voice, positioning, target-audience, brand-assets (pointers)
- [ ] **HITL branding pass** — confirming party signs off brand before volume posting. Hard rule: third-party article brands ≠ owner brand
- [ ] After pass: enforce **branding consistency** on drafts and gen assets
- [ ] **News / research preference (ask — not mandate):** Involve news and research process? Yes / No / Later. **Must ask** during onboarding even though this template is social media; research is **optional**. Save choice to profile memory
- [ ] **Content planning (light habit):** Agree a light planning cadence (e.g. weekly themes / inspiration → 靈感庫) — not a heavy calendar mandate

## 2. Flows (implant process)

- [ ] Create / configure **統籌** bot (dispatch + handoff rules; no publish without confirm)
- [ ] Create / configure **Social** bot (draft + schedule arrange; schedule-only after named version approve)
- [ ] Read-only connectivity test: Notion DBs + Metricool target account visible to the **chosen worker**; **no writes**
- [ ] Draft path: inspiration → 短文庫 fields (title, source, body/version, platform/account, images/episode, datetime+timezone, article link, review + result logs) → stop at 待審
- [ ] Human approval phrase/practice (version + platforms + body + images + time + links); bare "OK" is not enough
- [ ] **HITL (confirming party):** gen assets · visual design · **applications approval** (apps / accounts / Metricool brand use) — each needs explicit confirm before volume use
- [ ] Metricool schedule path only (Planning → create scheduled post); per-platform link handling noted (FB first comment; Threads often manual; IG Flow scoped to **this** post)
- [ ] Optional later: daily scan routine (example 08:00 owner timezone) with first Test run **read-only**; create only after owner confirms schedule + worker
- [ ] Optional: news/research intake into 靈感庫 **only if** owner chose Yes (or Later then Yes) — never invent research
- [ ] Post-publish confirmation flow (Metricool + native apps; store URLs in Notion)

**Gate:** Do not scale to volume posting until branding pass (§1b) is done and consistency is checked.

## 3. Folders (install required structure)

See also [folders.md](folders.md).

- [ ] Notion **靈感庫** (min: title, raw idea, source link) — test row without private data
- [ ] Notion **短文庫** (draft fields as in article / folders.md) — same test lineage
- [ ] **Sample short-post** in 短文庫 with **image and/or video paired** on the same row (rights-cleared; pointers in Notion + optional [assets/README.md](assets/README.md))
- [ ] This workstream wiki folder known to steward: `workshop/grok-bot-social-media-automation/` including `branding/`, `assets/`, `tone-and-voice/`
- [ ] Local/cloud place for images/media (media **not** in git — see REPO-RULES)
- [ ] Optional: skill/notes capture after first successful end-to-end post

## Done when

User (or guided bot) can open Notion DBs, see the correct Metricool accounts, has a saved **worker** choice and **news/research** preference, completed **branding pass** (or documented deferral with no volume posting), has one **sample paired** Notion short-post (write-up + image/video), and can complete **one** approved Metricool schedule + public confirmation without inventing data or skipping human approve (including gen-assets / visual-design / applications HITL).
