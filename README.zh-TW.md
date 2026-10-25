### Ted Chen

我是台灣的獨立 AI 工程師。語音 AI、LLM agent、智能合約都自己一個人做。大部分程式碼交給 Claude Code 和 Codex 寫，我負責決定要做什麼、review、測試、部署、上台 demo。

[English](README.md) · [作品集](https://tedinroc.github.io) · [LinkedIn](https://www.linkedin.com/in/tedinroc)

#### 2026

- **Eleven Seconds** · Monad Blitz 上海 V3 第一名（39 件作品中的第 1 名），單人參賽。智能合約升級的 30 個區塊冷卻期。三個 sentinel 程序各自持有私鑰，對新程式碼模擬攻擊，不變量被打破就在鏈上否決。僅測試網。
  [Arena](https://tedinroc.github.io/eleven-seconds-arena/) · [戰情室](https://tedinroc.github.io/eleven-seconds/) · [程式碼](https://github.com/tedinroc/eleven-seconds) · [官方結果](https://mojo.devnads.com/events/17?tab=showcase)
- **Upgrade Airlock** · ETH Shenzhen 2026 第二名，單人參賽。每次 proxy 升級都要先等過區塊冷卻期，再取得 Chainlink CRE 工作流的鏈上許可。工作流先在模擬器裡攻擊新實作，攻擊成功就發出簽名否決，升級不會執行。已部署在 Ethereum Sepolia。
  [戰情室](https://upgrade-airlock.pages.dev/) · [Demo 影片](https://upgrade-airlock.pages.dev/video/) · [程式碼](https://github.com/tedinroc/upgrade-airlock)
- **Isotherm** · Monad Metropolis Track 01（結果待公布）。Monad 測試網上的每日氣溫履約階梯，用 Chainlink CRE 工作流從機場 METAR 資料結算。149 個 Foundry 測試。
  [應用](https://tedinroc.github.io/isotherm/) · [Demo 影片](https://youtu.be/15AFL_xz_3U) · [程式碼](https://github.com/tedinroc/isotherm)
- **EARTHRISE** · Tripothon S1 參賽作品。真實月球高程資料，加上 Tripo 生成的地球，用 three.js 即時渲染。
  [場景](https://tedinroc.github.io/earthrise/) · [官方參賽頁](https://earthrise-daedalus.pages.dev/)
- **KAIKŌ** · 基於 OpenAI Realtime 和 WebRTC 的多租戶語音點餐。模型出錯時有確定的中英文備援，每個工具呼叫都在伺服器端檢查。
  [案例與 Demo 影片](https://tedinroc.github.io/kaiko/)
- **ESP32-S3 語音 agent 智慧手錶** · AMOLED 手錶上的語音 AI agent，建在 xiaozhi-esp32 和 ESP-Claw 上，搭配我自己寫的 Go 語音閘道。
  [專案網站（中文）](https://tedinroc.github.io/watch/)

這裡的東西都是測試網、demo 或原型。
