# 澎湖四天三夜分帳系統 🌊

一個專為四人旅遊打造的類似 Splitwise 即時同步分帳網站。採用澎湖海洋藍白風格設計，支援行動裝置優先的 RWD 響應式佈局。

## 🌟 核心功能特色

- **多人即時同步**：底層整合 Firebase Firestore，多人點擊相同連結進入房間即可即時同步所有開銷。
- **獨家連結房間系統**：自動產生獨立房間代碼，網址附加 `?room=XXXXXX` 即可一鍵邀請。
- **最佳化結算**：內建極簡債務清償演算法，一鍵精算「誰該給誰多少錢」，提供清晰的大字體提示，徹底免除人工計算煩惱。
- **全方位圖表分析**：引入 Chart.js，動態展示成員支付比例圓餅圖及類別支出分布長條圖。
- **防斷網離線備份**：內建離線備份機制與全量資料 JSON 導入/導出功能。

## 🛠️ 開發技術棧

- 前端架構：HTML5 / CSS3 (Tailwind CSS) / ES6+ JavaScript
- 資料庫支援：Firebase Firestore Realtime Database
- 圖表模組：Chart.js v4
- 圖示包：Font Awesome v6
- 雲端部署：GitHub Pages

## 🚀 快速開始指南

1. 將本專案複製或下載至本機環境。
2. 申辦 Firebase 帳號並開啟一個全新的 Cloud Firestore 實例。
3. 將 `index.html` 內的 `firebaseConfig` 變數內容，替換成你專案資料庫的專屬金鑰設定。
4. 將 `index.html` 直接上傳至 GitHub Pages，即可發布上線供親友使用！
