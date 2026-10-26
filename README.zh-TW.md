### Ted Chen

我在台灣做獨立開發，主要是語音 AI、LLM agent，以及智慧合約升級前的安全檢查工具。

[English](README.md) · [作品集](https://tedinroc.github.io/zh.html) · [LinkedIn](https://www.linkedin.com/in/tedinroc)

#### 2026 年作品

- **十一秒 Eleven Seconds** · Monad Blitz 上海 V3 第一名（共 39 件作品，單人參賽）。在 Monad 測試網上，合約升級要先等 30 個區塊；等待期間，三個 sentinel 程式會在模擬環境攻擊新程式碼，違反規則就在鏈上否決。
  [Arena](https://tedinroc.github.io/eleven-seconds-arena/) · [戰情室](https://tedinroc.github.io/eleven-seconds/) · [程式碼](https://github.com/tedinroc/eleven-seconds) · [官方結果](https://mojo.devnads.com/events/17?tab=showcase)
- **Upgrade Airlock 升級氣閘** · ETH Shenzhen 2026 第二名（單人參賽）。在 Ethereum Sepolia 測試網上，proxy 升級要先等冷卻期、拿到鏈上放行才能執行；Chainlink CRE 工作流會先模擬攻擊新實作，再決定放行或否決。
  [戰情室](https://upgrade-airlock.pages.dev/) · [Demo 影片](https://upgrade-airlock.pages.dev/video/) · [程式碼](https://github.com/tedinroc/upgrade-airlock)
- **Isotherm** · Monad Metropolis 參賽作品，結果待公布。在 Monad 測試網上，每天針對城市最高溫開一組 YES/NO 市場（履約價階梯），用機場 METAR 觀測資料結算。
  [App](https://tedinroc.github.io/isotherm/) · [Demo 影片](https://youtu.be/15AFL_xz_3U) · [程式碼](https://github.com/tedinroc/isotherm)
- **EARTHRISE** · Tripothon S1 參賽作品。用 three.js 做的月球場景：坑緣用真實高程資料重建，轉動曲柄，Tripo 生成的地球就從坑緣後方升起。
  [場景](https://tedinroc.github.io/earthrise/) · [官方參賽頁](https://earthrise-daedalus.pages.dev/)
- **KAIKŌ** · 語音點餐系統，走 OpenAI Realtime（WebRTC），目前用示範店家資料展示。模型的每個工具呼叫都要經過伺服器檢查，價格也由伺服器重算。
  [案例與錄影（英文）](https://tedinroc.github.io/kaiko/)
- **語音 agent 手錶** · ESP32-S3 個人原型，語音和裝置端 agent 分別用 xiaozhi-esp32 和 ESP-Claw，Go 語音閘道是我自己寫的。
  [專案網站](https://tedinroc.github.io/watch/)

大部分程式碼是 Claude Code 和 Codex 寫的，設計、審查、測試和部署由我負責。
