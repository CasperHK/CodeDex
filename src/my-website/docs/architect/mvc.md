---
sidebar_position: 1
---

# MVC（Model-View-Controller，模型-視圖-控制器）
Laravel 是一個開源的 PHP Web 應用框架，主要屬於 MVC（Model-View-Controller，模型-視圖-控制器）架構。

## 什麼是 MVC 架構？
MVC 是一種常見的軟體設計模式，將應用程式分成三個主要部分，讓程式碼更清晰、易維護和擴展：
*  Model（模型）：負責資料處理和業務邏輯，通常與資料庫互動。在 Laravel 中，主要透過 Eloquent ORM 實現，讓你用物件導向的方式操作資料庫。
*  View（視圖）：負責使用者介面的呈現，通常是 HTML 頁面。在 Laravel 中，使用 Blade 模板引擎 來產生動態視圖。
*  Controller（控制器）：負責處理使用者請求、協調 Model 和 View，處理輸入、呼叫模型取資料，然後傳給視圖顯示。

Laravel 從一開始就基於 MVC 模式設計，這讓開發者能快速建置結構化的 Web 應用程式。
Laravel 不只 MVC，還有哪些特色？
雖然核心是 MVC，但 Laravel 擴展了很多現代功能，讓它更強大：
*  服務容器（Service Container）：自動處理依賴注入（Dependency Injection）。
*  Middleware（中介層）：處理請求前的過濾（如驗證登入）。
*  Routing（路由）：簡單定義 URL 對應到控制器。
*  Facade（門面）：方便存取服務。
*  Eloquent ORM、Queue、Event 等：支援進階功能，如非同步任務、事件驅動等。
總之，Laravel 是典型的 MVC 框架，但結合了許多最佳實踐和工具，讓它適合從小型網站到大型企業應用都適用。如果你剛開始學，建議從官方文件（laravel.com/docs）入手，會清楚看到 MVC 的結構！如果有特定部分想深入了解，再告訴我哦～