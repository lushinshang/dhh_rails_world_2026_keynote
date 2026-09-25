# 拒絕黑色藥丸——DHH Rails World 2026 開場演講深度導讀

David Heinemeier Hansson（DHH）在 Rails World 2026 開場演講裡，用柯達 Brownie 相機平民化的攝影史，類比軟體開發正在經歷的同一種「摩擦力歸零」過程——起點是 2025 年 11 月 24 日 Claude Opus 4.5 發布的那一天。他講了自己如何從一年寫三萬行 Ruby，變成幾乎不再手寫程式碼；如何一邊痛罵 Rust 醜，一邊靠它把 Hey 後端的資源用量砍掉九成以上；也講了 CLI、Omarchy、自動化就業悖論與「Agent Luther」的宗教改革比喻。這篇深度導讀完整還原逐字稿內容，並對其中可查證的歷史與數字主張做了獨立查證，包括指出兩處他為了故事效果而簡化甚至誇大的數字。

## 200字介紹

DHH（Ruby on Rails 創造者、37signals 共同創辦人）在 Rails World 2026 開場演講：2025 年 11 月 24 日 Claude Opus 4.5 發布，是軟體業的分水嶺。過去 21 年每年寫 3 萬行 Ruby，現在幾乎不寫程式碼，37signals 宣告「pencils down」。他痛罵 Rust 醜，卻靠它把 Hey 後端 CPU 砍掉 99%；唯一要求：下週五前補齊 CLI。他說：別學那些看衰未來的悲觀主義者，選擇樂觀，全力加速。

完整導讀：https://lushinshang.github.io/dhh_rails_world_2026_keynote/

## 檔案清單

- `index.html` —— 發布用網頁（可直接用瀏覽器開啟）
- `dhh_rails_world_2026_keynote.md` —— 深度導讀 Markdown 原稿
- `images/` —— 4 組資訊圖表／插圖：
  - `summary-overview.png` + `summary-overview-mobile.png`（頁首「一圖看懂」全覽圖，桌面 16:9 / 手機 9:16，同時作為 OG／Twitter Card 分享預覽圖）
  - `timeline-photography-software.png` + `timeline-photography-software-mobile.png`（攝影×軟體平民化時間軸，桌面 16:9 / 手機 9:16）
  - `cli-universal-key.png`（CLI 通用協定概念圖，16:9）
  - `agent-luther-reformation.png`（Agent Luther 宗教改革意象，16:9）
- `research/`（本機保留，不建議公開）：
  - `source-ledger.md` —— 逐項查證紀錄，含 agy 首次摘要的兩處幻覺說明
  - `workflow-log.md` —— 完整製作流程紀錄
  - `image-prompts.md` —— 圖像生成提示詞規劃
  - `agy-transcript-read.txt` —— agy 初步逐字稿摘要（僅供參考，內容未經逐一核實，正式文章未採用其細節）
- `qa/`（本機保留，不建議公開）：
  - `desktop-1440x900-round-1.png`、`mobile-390x844-round-1.png`、`mobile-lightbox-round-1.png` —— 驗收截圖
  - `checks-round-1.md` —— 驗收記錄

## 原始來源

- 影片：Rails World 2026 Opening Keynote - DHH（YouTube）：https://www.youtube.com/watch?v=vDjW_dRyKXY
- 逐字稿：`transcription/Rails_World_2026_Opening_Keynote_-_DHH_vDjW_dRyKXY.srt`（本機路徑，958 個字幕區塊，時長 01:02:55；本文撰寫時已由主控 AI 逐行完整讀過一遍核對）

## 重要查證來源

- Anthropic 官方公告《Introducing Claude Opus 4.5》：https://www.anthropic.com/news/claude-opus-4-5
- Shopify Engineering《Migrating Shop app from React Native to native》：https://shopify.engineering/shop-app-migration
- Sackman, Erikson & Grant (1968), *Exploratory Experimental Studies Comparing Online and Offline Programming Performance*, CACM 11(1)：https://dl.acm.org/doi/10.1145/362851.362858
- 美國勞工統計局（BLS）職業就業統計：https://www.bls.gov/oes/
- David Heinemeier Hansson 個人網站：https://dhh.dk/
- 完整來源清單見文章末尾與 `research/source-ledger.md`

## 狀態

已發布。公開網址：https://lushinshang.github.io/dhh_rails_world_2026_keynote/
發布 repo：https://github.com/lushinshang/dhh_rails_world_2026_keynote
發布日期：2026-09-25。頁面已補上 Open Graph／Twitter Card meta tags 與「一圖看懂」全覽圖，LINE 等通訊軟體分享會顯示標題、描述與全覽圖預覽卡片。
