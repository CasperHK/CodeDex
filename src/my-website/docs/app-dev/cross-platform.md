---
sidebar_position: 1
---

# 跨平台應用
跨平台應用（Cross-Platform Application）是指開發一套程式碼，就能在 iOS、Android、Windows、macOS 等多種作業系統上運行，大幅降低開發成本與時間的應用程式開發方式。主要框架有 Flutter (Dart)、React Native (JavaScript/React) 和 Kotlin Multiplatform，它們透過共享大部分程式碼，實現多平台一致的體驗，並提供存取原生功能的介面，常用於需要快速開發且預算有限的項目。 

## 主要類型與框架

### Flutter
Flutter 是由 Google 開發的開源 UI 軟體開發工具包，使用 Dart 語言。它允許開發者使用單一程式碼庫來構建高效能的跨平台應用，支援 iOS、Android、Web 和桌面平台。Flutter 提供豐富的預製元件和強大的渲染引擎，使得應用具有一致的外觀和感覺。

### React Native
React Native 是由 Facebook 開發的開源框架，使用 JavaScript 和 React 庫。它允許開發者使用相同的程式碼庫來構建 iOS 和 Android 應用，並能夠存取原生元件和 API。React Native 強調熱重載功能，使開發過程更加高效。

### Svelte Native
Svelte Native 是基於 Svelte 框架的跨平台開發工具，允許開發者使用 Svelte 語法來構建原生移動應用。它結合了 Svelte 的高效能和 NativeScript 的原生功能，支援 iOS 和 Android 平台。Svelte Native 提供簡潔的語法和優化的性能，使得開發者能夠快速構建高質量的應用。

### Kotlin Multiplatform
Kotlin Multiplatform 是 JetBrains 開發的技術，允許開發者使用 Kotlin 語言撰寫共享程式碼，並在多個平台（如 Android、iOS、Web 和桌面）上編譯和執行。它支援原生效能和跨平台功能，同時保持了 Kotlin 的簡潔性和強大的類型系統。

### Compose Multiplatform
Compose Multiplatform 是 JetBrains 開發的跨平台 UI 框架，基於 Kotlin 語言。它允許開發者使用聲明式語法來構建用戶界面，並支援多個平台，包括 Android、iOS、桌面和 Web。Compose Multiplatform 強調可重用性和一致性，使得開發者能夠輕鬆地創建跨平台應用。

### Uno Platform
Uno Platform 是一個開源框架，允許開發者使用 C# 和 XAML 來構建跨平台應用。它支援 Windows、iOS、Android 和 WebAssembly，並且與 UWP（通用 Windows 平台）高度兼容，使得開發者可以輕鬆地將現有的 UWP 應用移植到其他平台。

### Xamarin
Xamarin 是由 Microsoft 擁有的跨平台開發框架，使用 C# 語言。它允許開發者使用單一程式碼庫來構建 iOS、Android 和 Windows 應用，並能夠存取原生 API 和元件。Xamarin 強調與 .NET 生態系統的整合，使得開發者可以利用現有的 .NET 技術和工具。

### Tauri
Tauri 是一個用於構建跨平台桌面應用的框架，使用 Rust 語言。它允許開發者使用前端技術（如 HTML、CSS 和 JavaScript）來構建應用界面，同時利用 Rust 提供的高效能和安全性。Tauri 支援 Windows、macOS 和 Linux 平台，並且具有較小的應用體積和低資源消耗。

### Iced
Iced 是一個用於構建跨平台 GUI 應用的 Rust 框架。它提供了一個簡潔且直觀的 API，使開發者能夠輕鬆地創建桌面和網頁應用。Iced 支援 Windows、macOS 和 Linux 平台，並強調響應式設計和組件化開發，適合需要高效能和現代化界面的應用程式。

### Dioxus
Dioxus 是一個用於構建跨平台應用的 Rust 框架，靈感來自於 React。它允許開發者使用聲明式語法來創建用戶界面，並支援多種平台，包括桌面（使用 Tauri 或其他後端）和 Web。Dioxus 強調高效能和易用性，適合需要現代化 UI 的應用程式開發。

### egui
egui 是一個用於構建跨平台 GUI 應用的 Rust 框架，專注於即時渲染和簡單易用的 API。它支援 Windows、macOS 和 Linux 平台，並且可以與多種渲染後端（如 wgpu）集成。egui 適合需要快速開發和高效能的應用程式，特別是在遊戲開發和工具製作方面。