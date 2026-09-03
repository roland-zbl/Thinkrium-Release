# Thinkrium Releases 🚀

<div align="center">

![Version](https://img.shields.io/badge/version-0.3.0-blue.svg?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-emerald.svg?style=flat-square)
![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Linux-orange.svg?style=flat-square)
![Electron](https://img.shields.io/badge/Electron-39-47848F.svg?style=flat-square&logo=electron)
![React](https://img.shields.io/badge/React-19-61DAFB.svg?style=flat-square&logo=react)

**專為深思者打造的本地優先個人知識作業系統 (Local-First Knowledge OS)**

[✨ 最新版本發布 (Releases)](https://github.com/roland-zbl/Thinkrium-Release/releases) • [💻 原始碼庫 (Source Code)](https://github.com/roland-zbl/thinkrium) • [📖 更新日誌 (Changelog)](https://github.com/roland-zbl/thinkrium/blob/main/CHANGELOG.md)

</div>

---

## 📥 最新版本快速下載 (v0.3.0)

請直接點擊下方連結下載最新穩定版本（2026-09-03 發布）：

| 平台 | 安裝檔案格式 | 檔案大小 | 官方直接下載連結 |
| :--- | :--- | :--- | :--- |
| 🍎 **macOS (Apple Silicon)** | `.dmg` (推薦) | **179.8 MB** | [👉 下載 `thinkrium-0.3.0.dmg`](https://github.com/roland-zbl/Thinkrium-Release/releases/download/v0.3.0/thinkrium-0.3.0.dmg) |
| 🍎 **macOS (Apple Silicon)** | `.zip` (免安裝) | **174.9 MB** | [👉 下載 `Thinkrium-0.3.0-arm64-mac.zip`](https://github.com/roland-zbl/Thinkrium-Release/releases/download/v0.3.0/Thinkrium-0.3.0-arm64-mac.zip) |
| 🪟 **Windows (64-bit)** | `.exe` (安裝檔) | **159.9 MB** | [👉 下載 `thinkrium-0.3.0-setup.exe`](https://github.com/roland-zbl/Thinkrium-Release/releases/download/v0.3.0/thinkrium-0.3.0-setup.exe) |
| 🐧 **Linux** | `.flatpak` (全桌面) | **145.0 MB** | [👉 下載 `thinkrium-0.3.0.flatpak`](https://github.com/roland-zbl/Thinkrium-Release/releases/download/v0.3.0/thinkrium-0.3.0.flatpak) |

> 💡 想要瀏覽過往歷史版本，請至 [GitHub Releases 頁面](https://github.com/roland-zbl/Thinkrium-Release/releases) 查看完整清單。

---

## 💡 什麼是 Thinkrium？(What is Thinkrium?)

在資訊碎片化與演算法推播主導的時代，我們的思考常被中斷、遺忘或分散在互不相通的雲端服務中。

**Thinkrium** 致力於打破「筆記軟體」、「RSS 閱讀器」與「資料卡片盒」的割裂邊界，以**本地優先 (Local-First)** 為根基，打造一個專注、純粹且高度關聯的深思空間：

1. **資料絕對主權 (Absolute Data Ownership)**：所有筆記、日記與概念百科均以純文字標準 Markdown 存儲於本地檔案系統（Vault），不綁定任何封閉雲端，可直接相容 Obsidian、Logseq 或 Git 版本控制。
2. **閉環工作流 (Closed-Loop Knowledge Flow)**：
   捕捉 (Capture) → 閱讀 (Read) → 提煉 (Extract) → 藏識湧現 (Emergence) → 創作 (Create)
3. **0ms 響應與沉浸體驗 (Desktop Performance)**：告別肥大 Electron 應用的卡頓與等待，全域頂層視圖 0ms 切換、閱讀串流維持 60fps 絲滑滾動、打字專注零干擾。

---

## ✨ 核心特色功能 (Core Features)

### 1. 📰 極速閱讀串流與靈感註解 (Feed Stream & Annotations)
- **非同步高效能閱讀**：重構資料管線，記憶體負擔驟降 95%，長列表滾動絲滑維持 60fps。
- **4 色劃線與即時註解**：選取內文即可呼出劃線工具，隨手記下即時想法（Annotation Popover），不丟失任何心流火花。
- **專注閱讀模式 (Zen Mode)**：按下快捷鍵 F 一鍵隱藏干擾，置中全覽排版，搭配微互動閱讀進度條。
- **文章雙向回溯**：自動過濾廣告與無效樣式，支援外部瀏覽器快速開啟 (O)。

### 2. ⚡ 動態素材副畫布與一拽入文 (Contextual Dock & Drag-to-Quote)
- **單一右側副畫布**：拒絕雙層側欄套疊！整合「📰 閱讀串流」、「🖍️ 劃線池」、「⚡ 隨行速寫」與「🔗 脈絡大綱」四大分頁，隨當前寫作情境智慧切換。
- **靈感一拽入文 (Drag-to-Quote)**：看見觸動思緒的文章段落或劃線金句，直接拖曳到編輯器中，立即轉化為帶有來源晶片的精緻標準引用卡片；每張素材卡片亦配備懸浮「➕ 引用」一鍵置入。
- **選取一鍵提升 (Promote to Entry/Note)**：在編輯器中選取靈感詞句，浮現一鍵提升為獨立筆記或概念藏識，原地自動替換為雙鏈晶片。

### 3. 📅 靈動日記時間流 (Fluid Daily Journal)
- **Heptabase 風格時間滑軌**：解放 100% 寫作空間！頂部 7 天橫向時間滑軌結合年月浮動日曆，跨月跳轉與當週切換零位移。
- **智慧延遲建立 (Lazy Creation)**：隨心翻閱過去或未來的日期，系統絕不提前生成無效空白 .md 檔案，只在您真正落筆打字時才為您建立日記。
- **零刷新時間戳快捷記錄 (Ctrl+Alt+T)**：隨時隨地在游標處插入即時時間戳，打字焦點 100% 保持，完全無感流暢。
- **今日足跡整合 (Daily Footprints)**：自動抓取當日所有已讀文章與劃線金句，支援一鍵點擊無縫注入日記。

### 4. 🗂️ 文庫全景卡片牆 (Library Cards Grid)
- **響應式卡片牆**：未選中筆記時展開 2~5 欄流式卡片牆，展示格式徽章、加粗標題、純文字精華摘要（Snippet）與標籤。
- **靈動雙欄寫作工作台**：點選任一卡片平滑切換 Master-Detail 雙欄寫作，並可隨時點擊「← 返回全覽」一鍵退回卡片網格。
- **多元排序與過濾**：支援關鍵字即時檢索、格式膠囊篩選，以及依最後修改、建立時間與標題排序。

### 5. 🧠 藏識系統 (Entry / 結構化概念物件)
- **結構化概念百科**：為概念、人物、產品、專案或公司建立具備元資料（Aliases、Properties）的知識卡片。
- **自動聚合與時間軸**：自動匯集全庫所有引用該藏識的筆記、關聯劃線金句，並按時間軸自動梳理思維演進軌跡。

### 6. 🔍 Spotlight 全域秒級搜尋與雙向鏈結
- **全域 Spotlight 搜尋條 (Ctrl+K)**：頂部一鍵呼出，採用 SQLite FTS5 全文檢索，支援簡繁互通與毫秒級快速穿透。
- **原子雙向鏈結**：支援行內 @ 呼出素材選單，支援 [[note:id|標題]] 與 [[entry:id|名稱]] 雙向網狀交織。

### 7. 🛡️ 堅如磐石的資料安全防線 (Rock-Solid Safety)
- **防空值覆蓋保護**：針對 Google Drive / iCloud / Nextcloud 等 rclone/FUSE 雲端掛載環境加入三重剛性安全防護，任何暫態空讀均絕對不會抹除硬碟既有內容。
- **本地雙保險回退**：本地資料庫與磁碟檔案建立雙向 Fallback 機制，斷網或同步延遲時內容永遠在線。
- **完整備份可攜**：支援一鍵匯出包含資料庫與筆記全量的完整 ZIP 備份包。

---

## 🍏 macOS 首次安裝使用說明

由於本開源發布包尚未向 Apple 申請付費開發者認證與公證 (Notarization)，首次安裝時 macOS Gatekeeper 可能會跳出「無法打開，因為無法驗證開發者」的提示：

1. **常規打開方式 (推薦)**：
   - 掛載下載的 `thinkrium-0.3.0.dmg`，將 Thinkrium 圖示拖入「應用程式 (Applications)」目錄。
   - 在「應用程式」目錄中找到 Thinkrium，按住鍵盤 Control 鍵點擊圖示（或點擊 **滑鼠右鍵**），選擇 **「打開」**。
   - 在彈出的系統對話框中點選 **「仍要打開」**，之後即可永久正常直接點擊開啟。
2. **終端機一鍵解除限制**：
   - 開啟系統「終端機 (Terminal)」應用程式，執行以下指令：
     ```bash
     xattr -cr /Applications/Thinkrium.app
     ```

---

## ⌨️ 常用快捷鍵 (Keyboard Shortcuts)

| 快捷鍵 | 功能作用 | 適用情境 |
| :--- | :--- | :--- |
| **Ctrl+K / Cmd+K** | 召喚 Spotlight 全域搜尋條 | 全域任意位置 |
| **Ctrl+1 ~ 5** | 快速切換頂層視圖（Dashboard / Library / Feed / Entry / Journal） | 全域任意位置 |
| **Ctrl+\ / Cmd+\** | 展開 / 平滑收合主導航側欄 | 全域任意位置 |
| **Ctrl+Alt+T** | 零刷新插入當前時間戳（如 # 15:30） | Journal 編輯器 |
| **F** | 進入 / 退出專注閱讀模式 (Zen Mode) | Feed 閱讀串流 |
| **J / K** | 切換上一篇 / 下一篇文章 | Feed 閱讀串流 |
| **M** | 標記為已讀 / 未讀 | Feed 閱讀串流 |
| **S** | 收藏 / 取消收藏文章 | Feed 閱讀串流 |
| **O** | 在系統預設外部瀏覽器開啟原始網頁 | Feed 閱讀串流 |

---

## 🔗 相關鏈接 (Links)

- 原始程式碼倉庫：[roland-zbl/thinkrium](https://github.com/roland-zbl/thinkrium)
- 提交 Bug 或功能建議：[Issues](https://github.com/roland-zbl/thinkrium/issues)
- 授權條款：[MIT License](https://github.com/roland-zbl/thinkrium/blob/main/LICENSE)
