---
title: Folders / data layout
workstream: grok-bot-social-media-automation
updated: 2026-10-31
---

# Folders

## In this FDE wiki (git)

```
workshop/grok-bot-social-media-automation/
├── index.md
├── template.md
├── onboarding.md
├── folders.md          ← this file
├── log.md
├── branding/
│   ├── index.md        ← purpose + hard rules; lists stubs
│   ├── tone-and-voice.md   (OPEN)
│   ├── positioning.md      (OPEN)
│   ├── target-audience.md  (OPEN)
│   └── brand-assets.md     (OPEN — pointers only)
├── tone-and-voice/
│   └── README.md       ← optional overflow; canon = branding/tone-and-voice.md
└── assets/
    └── README.md       ← media out of git; Notion image/video pairing
```

Related: `ideas/grok-bot-social-media-automation/` · `sources/creatorhome-grok-bot-social-media-automation.md`

**Hard rule:** third-party article brands ≠ owner brand. **Branding pass gate** before volume posting — see [branding/index.md](branding/index.md).

## Notion (implied by article — installer creates in their workspace)

| Database | Minimal fields (teaching minimum on the page) |
|----------|-----------------------------------------------|
| 靈感庫 | 標題、原始想法、來源連結 |
| 短文庫 | 標題；來源；正文與版本；平台與帳號；圖片與集數；預計發布時間（含時區）；文章連結／留言需求；審核紀錄；結果紀錄 |

**Sample paired post (onboarding):** one short-post write-up in 短文庫 with **image and/or video** linked on the same row (rights-cleared). Media binaries stay outside git; record pointers on the Notion row and optionally in [assets/README.md](assets/README.md).

Do **not** collapse write / approve / schedule / published into a single “done” state.

## Media

Images, video, and logos: Samba `agentOS/media` (or TBD) — **not** this git repo. See [../../REPO-RULES.md](../../REPO-RULES.md). Brand asset table: [branding/brand-assets.md](branding/brand-assets.md).
