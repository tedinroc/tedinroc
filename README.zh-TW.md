### Ted Chen

我是台灣的獨立 AI 工程師，獨立開發語音 AI、LLM agent 與智能合約工具。從問題定義、系統設計到部署皆由我負責；主要程式碼由 Claude Code 與 Codex 產出，之後由我審查、測試、部署並親自演示。

[English](README.md) · [作品集](https://tedinroc.github.io) · [LinkedIn](https://www.linkedin.com/in/tedinroc)

#### 2026 年代表作品

- **Eleven Seconds** · Monad Blitz 上海 V3 第一名（39 件作品中的第 1 名），單人參賽。為智能合約升級設計的 30 個區塊冷卻期。三個 sentinel 程序各自持有私鑰，對新程式碼執行攻擊模擬，於不變量遭破壞時在鏈上否決。僅限測試網。
  [Arena](https://tedinroc.github.io/eleven-seconds-arena/) · [戰情室](https://tedinroc.github.io/eleven-seconds/) · [程式碼](https://github.com/tedinroc/eleven-seconds) · [官方結果](https://mojo.devnads.com/events/17?tab=showcase)
- **Upgrade Airlock** · ETH Shenzhen 2026 第二名，單人參賽。每次 proxy 升級皆須通過區塊冷卻期，並取得 Chainlink CRE 工作流的鏈上許可。工作流會先在模擬器中攻擊新實作；若攻擊成功，升級將收到簽名否決而不會執行。已部署於 Ethereum Sepolia。
  [戰情室](https://upgrade-airlock.pages.dev/) · [Demo 影片](https://upgrade-airlock.pages.dev/video/) · [程式碼](https://github.com/tedinroc/upgrade-airlock)
- **Isotherm** · Monad Metropolis Track 01（結果待公布）。Monad 測試網上的每日氣溫履約階梯，透過 Chainlink CRE 工作流從機場 METAR 資料結算。149 項 Foundry 測試。
  [應用](https://tedinroc.github.io/isotherm/) · [Demo 影片](https://youtu.be/15AFL_xz_3U) · [程式碼](https://github.com/tedinroc/isotherm)
- **EARTHRISE** · Tripothon S1 參賽作品。真實月球高程資料，加上 Tripo 生成的地球，以 three.js 即時渲染。
  [場景](https://tedinroc.github.io/earthrise/) · [官方參賽頁](https://earthrise-daedalus.pages.dev/)
- **KAIKŌ** · 建構於 OpenAI Realtime 與 WebRTC 的多租戶語音點餐系統。模型失效時由確定的中英文備援接手，所有工具呼叫均於伺服器端驗證。
  [案例研究與 Demo 影片](https://tedinroc.github.io/kaiko/)
- **ESP32-S3 語音 agent 智慧手錶** · AMOLED 手錶上的語音 AI agent，建構於 xiaozhi-esp32 與 ESP-Claw，搭配自行開發的 Go 語音閘道。
  [專案網站（中文）](https://tedinroc.github.io/watch/)

本站內容均為測試網、演示或原型。
