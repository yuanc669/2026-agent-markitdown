# Markitdown — 萬能文件轉 Markdown 神器

## 對話開始時請先讀
進度與最近更動都在 Obsidian：`G:\我的雲端硬碟\Obsidian\Markitdown\工作筆記.md`

## 工作模式
- **加新工具**：對 Claude 說「我想做一個 XXX 工具」→ Claude 會建 `tools/<工具名>/` 子資料夾
- **結束工作**：對 Claude 說「**收工**」→ 自動 commit + push + 更新 Obsidian 工作筆記
- **接續工作**：對 Claude 說「讀工作筆記、告訴我上次做到哪」

## 工作桌 + 三個家
- 📋 GDrive 工作桌：`G:\我的雲端硬碟\Claude_AI_Agents\2026_agent_markitdown\`（自動跨電腦同步）
- 🐙 GitHub repo：`yuanc669/2026-agent-markitdown`（公開，網頁的家）
- 📘 Obsidian 駕駛艙：`G:\我的雲端硬碟\Obsidian\Markitdown\工作筆記.md`（想法的家）

## 進件 Inbox
- `G:\我的雲端硬碟\_inbox\data\`    ← 待轉換的原始數據
- `G:\我的雲端硬碟\_inbox\text\`    ← 待轉換的文件（PDF、DOCX、PPTX 等）
- `G:\我的雲端硬碟\_inbox\images\`  ← 待轉換的圖片
- `G:\我的雲端硬碟\_inbox\tasks.md` ← 待辦任務佇列
- `G:\我的雲端硬碟\_inbox\urls.md`  ← 待研究連結清單

## 工具清單
（之後加新工具時會自動更新）
- （尚無）

## 工作注意事項
- commit 訊息要寫清楚做了什麼 + 為什麼
- 收工前說「收工」讓 Claude 同步三方
- `.claude/` 永遠不要 commit
