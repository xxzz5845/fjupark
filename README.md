停車觀察系統 - 輔仁大學周邊
簡介

本系統旨在提供輔仁大學周邊機車停車位的即時資訊，幫助機車騎士迅速了解停車狀況，減少找尋停車位的時間，提升停車效率。

功能特色

即時停車資訊：顯示停車場當前剩餘車位狀況

地圖標示：整合 Google Maps，標示各停車場位置與詳細資訊

使用者回報機制：機車騎士可即時回報停車場現況，確保資訊即時性

檢舉系統：使用者可檢舉錯誤資訊，確保數據準確性

收費資訊：顯示停車場是否為免費或收費，以及費率資訊

使用者登入與註冊：提供電子郵件及社群媒體登入功能，確保便利性

技術架構

1. 前端技術

HTML5 / CSS3 / JavaScript：負責網頁結構與樣式

Bootstrap：提升響應式介面體驗

jQuery：強化互動性與動態功能

Google Maps API：地圖整合與停車場標記

2. 後端技術

Firebase：負責使用者身份驗證與數據存儲

Node.js / Express.js：作為 API 伺服器

Firestore：用於存儲即時回報資訊

3. 資料庫

Firebase Firestore：存儲使用者帳號、回報資訊及點數系統

安裝與運行方式

環境需求

Node.js 16+

Firebase 設定（需在 database.js 內配置）


使用方式

使用者可透過登入/註冊系統進入。

在首頁地圖上查看輔仁大學周邊停車場。

點擊停車場標記以獲取詳細資訊（剩餘車位、收費方式等）。

可透過即時回報功能更新停車場現況。

若發現錯誤資訊，可使用檢舉功能進行回報。




