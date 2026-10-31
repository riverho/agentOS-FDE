---
title: Onboarding checklist stub
workstream: grok-bot-social-media-automation
updated: 2026-10-31
---

# Onboarding checklist (stub)

Order locked by River (2026-10-31 ~15:28 HKT): **tools → flows → folders**, then work starts. Contents below are filled from what the third-party article **implies** — not a claim that River's shipped checklist already exists as product copy.

Blueprint: https://creatorhome.tw/articles/grok-bot-social-media-automation

## 1. Tools (install / sign-in / connect)

- [ ] Grok Bot installed and signed in (Mac app per article; account/plan per official docs)
- [ ] Notion signed in; can open intended databases
- [ ] Metricool signed in; brand linked to the IG / Threads / FB accounts that will publish (verify names/handles, not just avatars)
- [ ] Codex **or** Claude Code on Mac signed in (separate from Grok Bot login)
- [ ] First-round scope chosen: one platform, one short post, one rights-cleared image

## 2. Flows (implant process)

- [ ] Create / configure **統籌** bot (dispatch + handoff rules; no publish without confirm)
- [ ] Create / configure **Social** bot (draft + schedule arrange; schedule-only after named version approve)
- [ ] Read-only connectivity test: Notion DBs + Metricool target account visible to executor; **no writes**
- [ ] Draft path: inspiration → 短文庫 fields (title, source, body/version, platform/account, images/episode, datetime Asia/Taipei, article link, review + result logs) → stop at 待審
- [ ] Human approval phrase/practice (version + platforms + body + images + time + links)
- [ ] Metricool schedule path (Planning → create scheduled post); per-platform link handling noted (FB first comment; Threads often manual; IG Flow scoped to **this** post)
- [ ] Optional later: daily scan routine (example 08:00 Asia/Taipei) with first Test run **read-only**
- [ ] Post-publish confirmation flow (Metricool + native apps; store URLs in Notion)

## 3. Folders (install required structure)

See also [folders.md](folders.md).

- [ ] Notion **靈感庫** (min: title, raw idea, source link) — test row without private data
- [ ] Notion **短文庫** (draft fields as in article / folders.md) — same test lineage
- [ ] This workstream wiki folder known to steward: `workshop/grok-bot-social-media-automation/`
- [ ] Local/Samba place for images/media (media **not** in git — see REPO-RULES)
- [ ] Optional: skill/notes capture after first successful end-to-end post (article step 9)

## Done when

User (or guided bot) can open Notion DBs, see the correct Metricool accounts, and complete **one** approved schedule + public confirmation without inventing data or skipping human approve.
