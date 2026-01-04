# 📖 CodeDex - 現代編程語言與生態指南

CodeDex 是一個基於 Docusaurus 構建的開源文檔計畫。我們致力於整理 2026 年主流及新興編程語言的核心特性，並精選各語言生態系中最值得推薦的函式庫（Libraries），幫助開發者在技術浪潮中快速定位工具。

## 🌟 核心特點
直擊重點：拒絕長篇大論，僅收錄語言最具代表性的特徵與應用場景。
生態優先：針對每種語言推薦當前最流行、維護最穩定的「精選庫清單」。
繁體中文：全站採用標準繁體中文，為華語開發者提供第一手的技術導航。
現代審美：基於 Docusaurus 3+，支援深色模式、全文檢索及極致的閱讀體驗。

## 🛠 快速啟動

### 前置要求
Node.js (建議版本 18.0 以上)
Yarn 或 npm

### 安裝步驟
1. 複製專案
   ```bash
   git clone github.com
   cd codedex
   ```
 
2. 安裝依賴
   ```bash
   pnpm install
   ```   
3. 啟動本地開發伺服器
   ```bash
   yarn start
   ```
   
4. 啟動後，在瀏覽器打開 http://localhost:3000 即可預覽。

### 構建靜態網站

```bash
yarn build
```


## 📂 資料夾結構
* **/docs:** 存放所有語言的介紹與函式庫文檔（Markdown 格式）。
* **/src/pages:** 存放自定義頁面。
* **/static:** 存放圖片、圖示等靜態資源。
* **docusaurus.config.js:** 全站設定檔（包含標題、側邊欄導航等）。

---

## 🤝 參與貢獻
我們非常歡迎任何形式的貢獻！
1. Fork 本倉庫。
2. 建立您的 Feature Branch (git checkout -b feature/NewLanguage)。
3. Commit 您的修改 (git commit -m 'Add New Language: Mojo')。
4. Push 至遠端分支 (git push origin feature/NewLanguage)。
5. 發起 Pull Request。

## 📄 開源協議
本專案採用 MIT License 協議授權。

---

CodeDex —— 讓技術選擇不再困難。
