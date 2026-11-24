# 何昱陞 (Eason Ho) - 個人面試簡歷網站

> **副標題**：尋找實習機會｜AI 應用開發 × 數位資訊組織 × 數據與內容整合  
> **技術架構**：純靜態單頁（HTML5 + Tailwind CSS + 互動 JS + 響應式優化 + 列印 PDF 排版優化）

---

## 專案亮點與特色

1. **零編譯門檻**：純靜態單一 HTML 架構，不需安裝 Node.js、npm 或任何打包工具。
2. **面試官專用快捷視角（Quick Perspective Filter）**：
   - 🌟 **全方位視角**：展示完整經歷與專案能力。
   - 💻 **資訊科技與知識服務（神通資訊、飛資得）**：自動高亮 Python、Java Spring Boot、SQL、本地 RAG 知識庫與資訊組織架構。
   - 🎬 **新媒體串流與整合行銷（三立電視、DAZN、傳揚）**：自動高亮 GenAI 工具應用、CapCut 剪輯、短影音獲獎經歷、Flourish 數據視覺化與跨團隊溝通能力。
3. **面試官體驗友善**：
   - 支援手機、平板、電腦自適應響應式螢幕。
   - 支援深淺色（Dark / Light Mode）無縫切換。
   - 一鍵列印 / 匯出 PDF（已預先設定 `@media print` 專用無干擾標準排版）。
   - 一鍵複製 Email、手機點擊直撥、作品集 QR Code 彈窗放大檢視。

---

## 檔案目錄結構

```text
個人履歷/
├── index.html               # 履歷網站主程式（直接雙擊即可在本機瀏覽器打開）
├── assets/
│   ├── avatar.jpg           # 個人正式形象大頭照
│   └── portfolio_qr.png     # 作品集 QR Code 圖片
└── README.md                # 專案說明與 GitHub Pages 上線部署教學
```

---

## 本機預覽方式

1. 打開資料夾 `c:\Users\Eason\Desktop\個人履歷`。
2. 對著 `index.html` **按滑鼠右鍵 -> 開啟檔案 -> 選擇 Chrome / Edge 或任何瀏覽器**（或直接連按兩下滑鼠左鍵）。
3. 即可立即在瀏覽器中完整預覽與操作！

---

## 如何在 GitHub 免費部署上線（GitHub Pages 3 分鐘教學）

因為本專案為**純靜態架構**，完全不需要伺服器，直接使用 GitHub Pages 就能取得專屬公開網址！

### 步驟 1：建立 GitHub 倉庫 (Repository)
1. 登入 [GitHub](https://github.com/)（若無帳號請先註冊）。
2. 點擊右上角 **「+」** -> 選擇 **「New repository」**。
3. 設定倉庫名稱：
   - **方式 A（個人專屬首頁，強烈推薦）**：將 Repository name 命名為 `你的帳號名稱.github.io`（例如若你的帳號是 `easonho`，就取名 `easonho.github.io`）。這樣你的履歷網址就會是最頂級簡短的：`https://easonho.github.io`。
   - **方式 B（一般專案網址）**：Repository name 取名為 `resume` 或 `cv`，後續網址會是 `https://你的帳號名稱.github.io/resume`。
4. 設定為 **Public（公開）**。
5. 勾選 **Add a README file**（或不勾選皆可），點擊綠色的 **「Create repository」**。

---

### 步驟 2：上傳檔案到 GitHub
1. 進入剛建好的 GitHub 倉庫頁面，點擊右上方的 **「Add file」** -> **「Upload files」**。
2. 將電腦中 `個人履歷` 資料夾裡的所有內容拖曳進去：
   - `index.html`
   - `assets` 資料夾（包含裡面的 `avatar.jpg` 與 `portfolio_qr.png`）
   - `README.md`
3. 拖曳完成後，在下方 Commit changes 處直接點擊綠色的 **「Commit changes」** 按鈕儲存。

---

### 步驟 3：啟用 GitHub Pages 免費託管
1. 在倉庫上方選單點擊 **「Settings」**（齒輪圖示）。
2. 在左側欄位點擊 **「Pages」**。
3. 在 **Build and deployment** 下方的 **Branch**：
   - 選擇 **`main`**（或 `master`）。
   - 資料夾選擇 **`/ (root)`**。
   - 點擊 **「Save」**。
4. 稍等 1～2 分鐘，重新整理頁面，頂部就會出現綠色的提示訊息：  
   👉 **`Your site is live at https://你的帳號.github.io/`**！

---

### 步驟 4：面試時如何使用
- 將產生的 GitHub Pages 網址貼在你的數位履歷、104 / 1111 求職自傳、CakeResume 或 LinkedIn 上。
- 現場面試時，可以用手機或平板打開該網址直接展示給面試官看，並點擊頂部的 **「面試官視角切換器」** 針對神通、飛資得、三立、DAZN、傳揚等不同企業需求切換對應重點！
