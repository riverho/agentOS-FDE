---
title: Onboarding checklist — Social Media Automation
workstream: grok-bot-social-media-automation
updated: 2026-10-31
---

# Onboarding checklist

Order locked by River (2026-10-31 ~15:28 HKT): **tools → flows → folders**, then work starts.

Aligned with staged template **Social Media Automation** v1 (CreateBotShareJson 2026-10-31 ~18:35 HKT) and River design notes: **ask worker choice** (likely Grok Bot worker); **Metricool fixed** (automation focus — do not offer many schedulers).

Blueprint (facts only): https://creatorhome.tw/articles/grok-bot-social-media-automation

## 1. Tools (install / sign-in / connect)

- [ ] Grok Bot installed and signed in
- [ ] Notion signed in; can open intended databases (靈感庫 + 短文庫) — create minimal DBs if missing
- [ ] **Metricool** signed in; brand linked to the IG / Threads / FB accounts that will publish (verify names/handles, not just avatars). **Do not** pitch Buffer, Later, or other schedulers
- [ ] **Worker choice (required — ask owner):** Grok Bot worker (recommended default) · Mac Codex · Mac Claude Code · Manual (copy-pasteable briefs only). Save to profile memory. If Mac options need a machine online, say so when relevant
- [ ] Timezone for schedules chosen (e.g. Asia/Hong_Kong or Asia/Taipei)
- [ ] First-round scope chosen: one platform, one short post, one rights-cleared image

## 2. Flows (implant process)

- [ ] Create / configure **統籌** bot (dispatch + handoff rules; no publish without confirm)
- [ ] Create / configure **Social** bot (draft + schedule arrange; schedule-only after named version approve)
- [ ] Read-only connectivity test: Notion DBs + Metricool target account visible to the **chosen worker**; **no writes**
- [ ] Draft path: inspiration → 短文庫 fields (title, source, body/version, platform/account, images/episode, datetime+timezone, article link, review + result logs) → stop at 待審
- [ ] Human approval phrase/practice (version + platforms + body + images + time + links); bare "OK" is not enough
- [ ] Metricool schedule path only (Planning → create scheduled post); per-platform link handling noted (FB first comment; Threads often manual; IG Flow scoped to **this** post)
- [ ] Optional later: daily scan routine (example 08:00 owner timezone) with first Test run **read-only**; create only after owner confirms schedule + worker
- [ ] Post-publish confirmation flow (Metricool + native apps; store URLs in Notion)

## 3. Folders (install required structure)

See also [folders.md](folders.md).

- [ ] Notion **靈感庫** (min: title, raw idea, source link) — test row without private data
- [ ] Notion **短文庫** (draft fields as in article / folders.md) — same test lineage
- [ ] This workstream wiki folder known to steward: `workshop/grok-bot-social-media-automation/`
- [ ] Local/cloud place for images/media (media **not** in git — see REPO-RULES)
- [ ] Optional: skill/notes capture after first successful end-to-end post

## Done when

User (or guided bot) can open Notion DBs, see the correct Metricool accounts, has a saved **worker** choice, and complete **one** approved Metricool schedule + public confirmation without inventing data or skipping human approve.
