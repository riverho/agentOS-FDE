---
title: Grok Bot 怎麼開始用？超完整解析與案例分享
source: https://creatorhome.tw/articles/grok-bot-guide
author: 郭政佑 Kevin
site: 創作邦 (creatorhome.tw)
published: 2026-09-10
updated: 2026-10-22
ingested: 2026-10-24
owner: DimSum
tags: [grok-bot, guide, creatorhome, brand]
---

# Grok Bot 怎麼開始用？超完整解析與案例分享

> Canon wiki copy of the published article. Prefer linking readers to the [public page](https://creatorhome.tw/articles/grok-bot-guide). Use this file for agent context, summaries, and brand-consistent reuse.

作者：郭政佑 Kevin · 發布於 2026-09-10 · 內容更新 2026/10/22

## 摘要

社群分享 Grok Bot 心得後迴響不錯。本文解析心得、方案、怎麼開始用，以及官方／案例／GitHub 資源入口；並說明與 Codex、Claude Code、Hermes 等 Agent 的差異。

**2026-10-22 更新：** Grok Bot 現在可以建立報告、備忘錄與儀表板頁面。可請 Bot 先建好頁面再一起改，或讓它持續更新。（功能陸續提供給最新版手機與桌面 App。）

**2026-10 更新：** 補上整理成 IG 圖卡的用法——JEV 派工、Herdr 控制本機 agent、在 X 上標記、排程、「重要的事先問過我」的自動審核規則。

## Grok Bot 官方入口

資格與功能以當下官方說明為準：

- 官方總覽
- Get started（安裝／建立 Bot）
- Plans and billing（資格／額度／計費）
- FAQ
- Guides 索引
- 如何同時運作多個 Grok Bot 團隊
- 用 Grok Bot 設計 Grok Bot
- Bot Marketplace

## 值不值得用？結論

當下非常好用，但不保證永遠鎖定同一工具——AI 變化快，工具可能幾個月就換。功能上與 Codex / Claude Code 能做的事相近；**最大差異在便利性與打通體驗**：

### 多裝置互通

桌機與手機同一帳號可接續同一個 Bot。處理本機檔案需授權該電腦的本機指令。常用情境：手機一句話「把檔案從 A 搬到 B」、或「把兩台電腦上 agent 紀錄整理成一份」（兩台都開著、已授權）。

### 關電腦還能做事

關掉本機後，帳號下 Bot 仍共用一台雲端電腦：瀏覽器、可安裝 CLI（Codex / Cursor / Claude Code 等，各自登入）。只有手機也能維持辦公與自動化。

## 方案怎麼選？

- **初次嘗試：** Premium（月 $30 / 年 $300），週額度約為 Plus 的 4 倍。Plus（月 $8）**不含** Grok Bot。
- **用量大：** Super（月 $100 / 年 $1,000），約 Plus 的 15 倍。
- **更多：** Ultra（月 $200 / 年 $2,000），約 Plus 的 50 倍。

新方案 The X Subscription：Premium / Super / Ultra 都含 Grok Bot、雲端 agent 與自動化；Super 有尖峰優先，Ultra 有最早使用權。Grok Bot 與 Grok、Cursor 合資格第一方模型共用每週額度池；第三方模型另計；超過額度用 Additional Usage credits。舊 Cursor Pro / Pro+ 等仍可用 Bot，資格以 Plans and billing 為準。

## 怎麼開始用？第一隻建議當總管

1. 從官方下載頁安裝 App 並登入。
2. 第一隻 Bot 設成**總管**：管理其他 Bot、分配任務。
3. Bot 之間可互傳訊息；可請總管一次設計／建立多個 Bot。
4. 每個 Bot 可設：例行任務、描述與目的；各自有記憶與做法。
5. **注意：** 同帳號 Bot 共用雲端電腦——角色分工 ≠ 資料隔離。

## 市集：Plugins 與現成 Bot

- **Plugins：** Gmail、Notion、Google Calendar 等；授權範圍依服務而定。作者實務曾連多個 Gmail。
- **下指令：** 講清「哪個工具 + 要做什麼」（例：「整理今天 Slack 需回覆的訊息」）。
- **市集 Bot vs Skill：** Bot 是完整角色（指示、記憶、技能、例行、外掛）；匯入不會帶走原作者電腦／登入／對話。

## 操作小技巧

- **X 標記 @bot：** 先在 grok.com Settings › Account 連結 X；帶影片／GIF 的貼文目前不接單。
- **API／Token：** 用專門安全輸入，不貼進一般對話。
- **例行任務：** 對話建立排程；對外發文草稿先確認再發。
- **重要事先問：** 對外發訊、刪除、付款等先停等確認；可在 Settings › General › Auto-review 自訂規則（Ask first 優先）。
- **Linux 主機：** 可裝 AI CLI；作者實務會登入 Gemini 協助理解 YouTube 公開內容（非官方內建轉交）。

## 團隊設計：總管、Leader、專職

- 一定有總管；大專案再設 Leader；領域專職（財務、Code、社群等）。
- 側邊欄可隱藏 Bot，仍由總管呼叫。
- 用待辦（如 Notion）與 Bot 一起追進度；可參考 Status Report Writer 範本。
- 習慣用長期「角色」分工，而非純 Session／Skill。

## 派工到本機：JEV 與 Herdr

- **JEV（TypeSafe / Jev）：** 快速結構化判斷（Choice / Score / Noul），用來分流派工；社群有 Jev router 模板，非 xAI 官方。
- **Herdr：** 開源終端把 Codex、Claude Code、Cursor 等 CLI 放同畫面；agent 之間也可互相接手。
- 模式：Grok Bot 統籌 → 本機 Claude Code／Codex 動手 → 結果回 App 確認。

## 最有感的地方

體驗「無感」——任務分得清楚、手機就能處理多數工作。模型由服務管理；專業需求仍可走特定 CLI 或 Cursor 選模。Grok Bot 像中控中心。

## 價格怎麼想

對比人力成本：若能省大量心力與雜事，訂閱費可合理。願意付較高費是因為真的幫上忙。

## 延伸資源

- **X：** [@bot](https://x.com/bot) 官方；[@poteto](https://x.com/poteto) 實作向分享。
- 案例多為展示或個人說法；留意實測／觀點／未驗證。

## FAQ（文內）

1. **跟一般 Grok 聊天差在哪？** Bot 是具名持久助理，能在雲端接工具把結果寫進 Notion／日曆／檔案。
2. **一定要 Super？** 不必；可先 Premium。Plus 不含 Bot。
3. **多開 Bot 資料會隔離？** 不會；同帳號共用雲端電腦。
4. **寄信／發文／購買可全交？** 查找整理草擬可先交；對外生效與難復原的最後一關留人。
5. **更多真實用法？** Guides、Marketplace、@bot、文末 X／GitHub；實作前再對官方文件。

---

*Ingested for brand llm-wiki. Steward: DimSum. Do not treat price/plan numbers as forever-fixed—verify against official Plans and billing before publishing anew.*

## Connections

- **Big idea:** [[concepts/brand-thesis|Brand thesis]] — Grok Bot as a practical vehicle so one-person operators and SMBs can *act* on ideas (multi-bot teams, routines, safe outbound), not just read about AI.
- **Audience fit:** SMBs and individuals hungry to learn tooling and land workflows; fills gaps on plans, setup, multi-device, Auto-review, and local agent handoff (JEV / Herdr).
- **Upstream:** reader already curious about AI agents / productivity tooling.
- **Downstream gaps we may still need pages for:** Creator Home product line beyond this guide; SMB landing-page playbooks; “from idea to first shipped asset” checklist; Chinese/English voice guide for the brand.
- **Source:** [[sources/creatorhome-grok-bot-guide|source metadata]] → https://creatorhome.tw/articles/grok-bot-guide
