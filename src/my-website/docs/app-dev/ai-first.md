---
sidebar_position: 1
---

# AI 友好框架

### AI 對 Nuxt.js 和 Vue 的友好度

在 2026 年初的 **AI Coding**（尤其是 Vibe Coding：用自然語言引導 AI 如 Cursor、Claude、Copilot 生成程式碼）環境下，**Vue.js 和 Nuxt.js 對 AI 是「中等友好」**，但不如 React/Next.js 或 SolidJS 那麼順手。Vue 生態成熟，但 LLM（大型語言模型）的訓練資料以 React 為主，導致生成 Vue/Nuxt 程式碼時偶爾出錯或需要更多修正。以下是基於社區實戰反饋和趨勢的分析。

#### 優勢：Vue/Nuxt 在 AI 時代的強項
- **Nuxt 團隊積極擁抱 AI**：Nuxt 4（2025 年發布）官方提供了 **llms.txt** 機制，這是專門為 LLM 設計的文件，讓 AI 工具（如 Cursor、Claude、Copilot）更容易理解 Nuxt 的概念、API 和最佳實踐。官方文件甚至有專章教導如何優化 AI 體驗。這是 Nuxt 的獨特優勢，其他框架（如 SolidJS 或 Remix）還沒類似官方支援。
- **語法相對簡單**：Vue 的單文件組件（SFC）、Composition API 和 Options API 直觀，AI 生成基本 UI（如表單、列表）時準確率高。許多人反饋，AI 能正確生成 Nuxt 的自動路由和單文件組件。
- **實戰正面案例**：
  - Nuxt 領袖 Daniel Roe 公開展示用 AI Vibe Coding 建置並部署 Nuxt app。
  - 有些開發者用 Cursor 成功 Vibe Coding 出 Nuxt 4 PWA（如學習希臘字母的閃卡 app），並分享經驗。
  - 有人表示「AI 寫了我 90% 的 Nuxt 程式碼」，只要 codebase 結構好，Cursor 不會掙扎。

#### 缺點：AI 常踩的坑
- **訓練資料不足**：React 是 LLM 最熟悉的框架（訓練資料量最大），Vue/Nuxt 排第二或第三。AI 容易混淆 Vue 3 的 Composition API、Nuxt 4 的目錄結構（pages 要放 app 目錄下），或生成過時的 Nuxt 3 程式碼。
- **Vibe Coding 體驗不穩定**：
  - 有人試用 Claude 寫 Nuxt 4，AI 一直打轉無法顯示頁面。
  - 反饋指出：「Cursor 等工具在非主流栈（如 Nuxt）上掙扎，修正成本高，转而用 Next.js。」
  - 社區討論：很多人從 Nuxt 轉 Next.js 純粹因為 AI 生成更快、更準。

## AI 友好度排序
  | 框架          | AI 友好度 | 原因簡述                          | 適合 Vibe Coding 情境 |
  |---------------|-----------|-----------------------------------|-----------------------|
  | React/Next.js | ★★★★★    | 訓練資料最多，生成最準            | 首選，快速原型       |
  | SolidJS       | ★★★★☆    | 語法像 React，實戰順手            | 高性能 UI            |
  | Remix         | ★★★★☆    | AI-First 設計，通用程式碼易整合   | 未來潛力大           |
  | Vue/Nuxt      | ★★★☆☆    | llms.txt 幫忙，但偶爾混淆         | 已熟悉 Vue 的開發者  |
  | Svelte        | ★★★☆☆    | Svelte 5 語法變化讓 AI 易錯       | 小專案               |

#### 結論與建議
- **如果已經熟悉 Vue/Nuxt**：AI 絕對夠用！用 llms.txt 優化提示，搭配 Cursor 或 Claude，能大幅加速開發（尤其是全端 SSR 應用）。很多人仍堅持 Nuxt 因為開發體驗佳 + AI 輔助。
- **如果從零開始 Vibe Coding**：建議優先 React/Next.js 或 SolidJS，AI 生成的程式碼更少 bug，迭代更快。
- **2026 年展望**：隨著 Nuxt 的 llms.txt 普及和更多訓練資料，Vue/Nuxt 的 AI 友好度會提升。但短期內，React 仍主導 AI 驅動開發。

如果你有特定功能想測試（例如讓我 Vibe 一段 Nuxt 程式碼），告訴我需求，我可以試試看～