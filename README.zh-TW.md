# Ted Chen

台灣的獨立 AI 工程師，主要開發**語音 AI、agent 與鏈上安全工具**。

[English](README.md) · [作品集](https://tedinroc.github.io/zh.html) · [X](https://x.com/tedinroc) · [LinkedIn](https://www.linkedin.com/in/tedinroc)

## 精選作品

- **[GapCaster](https://github.com/tedinroc/gapcaster)** — 離線產生口述影像，把旁白安排在對白空隙；每句附有依據，並提供人工審閱。**ASUS UGen AI League 2026 決賽入圍。**目前為筆電原型。  
  [範例影片](https://github.com/tedinroc/gapcaster/blob/main/samples/tears-of-steel-0-140/clip_with_ad.mp4) · [輸出範例](https://github.com/tedinroc/gapcaster/tree/main/samples/tears-of-steel-0-140)
- **[Remote Hands](https://github.com/tedinroc/remote-hands)** — 透過主控台修復 Linux 測試伺服器，獨立程式檢查重開機、SSH 與資料完整性。**受控測試環境中的原型。**  
  [介紹影片](https://youtu.be/1kL6B0gGCck) · [實際執行回放](https://tedinroc.github.io/remote-hands/)
- **[Undo for Bitcoin](https://github.com/tedinroc/undo)** — 使用 NEAR Chain Signatures，替 Bitcoin 支出加入等待期、手機 passkey 取消與冷金鑰復原。**NEAR 測試網 + Mutinynet。**  
  [展示影片](https://undo-btc.pages.dev/) · [驗證步驟](https://github.com/tedinroc/undo#run-it)
- **[十一秒 Eleven Seconds](https://github.com/tedinroc/eleven-seconds)** — 三個 sentinel 在升級的 30 區塊冷卻期內模擬攻擊，違反規則便否決。**Monad Blitz 上海 V3 第一名，單人參賽。**Monad 測試網。  
  [親手測試攻擊卡](https://tedinroc.github.io/eleven-seconds-arena/) · [官方結果](https://mojo.devnads.com/events/17?tab=showcase)
- **[Upgrade Airlock 升級氣閘](https://github.com/tedinroc/upgrade-airlock)** — 合約升級須經過冷卻期，並取得 Chainlink CRE 模擬檢查後的放行。**ETH Shenzhen 2026 第二名，單人參賽。**Sepolia 測試網。  
  [展示影片](https://upgrade-airlock.pages.dev/video/) · [戰情室](https://upgrade-airlock.pages.dev/)
- **[Isotherm](https://github.com/tedinroc/isotherm)** — 以 METAR 資料結算城市氣溫市場，包含 Kuru 訂單簿與 MetaMask Agent Wallet 外掛。**Monad Metropolis 的 MetaMask 賞金獎得主（US$750）。**Monad 測試網。  
  [開啟 App](https://tedinroc.github.io/isotherm/) · [展示影片](https://youtu.be/15AFL_xz_3U) · [得獎紀錄](https://github.com/tedinroc/isotherm/blob/main/docs/awards/metropolis-metamask-bounty.png)

## 其他實驗

- [KAIKŌ](https://tedinroc.github.io/kaiko/) — 語音點餐，工具呼叫與價格都由伺服器驗證；附示範店家的完整點餐錄影。
- [語音 agent 手錶](https://tedinroc.github.io/watch/) — 基於 xiaozhi-esp32 與 ESP-Claw 的 ESP32-S3 原型，搭配我開發的 Go 語音閘道。
- [EARTHRISE](https://tedinroc.github.io/earthrise/) — 使用真實高程資料與 Tripo 生成的地球，製作 three.js 月球場景。

## 開發方式

系統由我設計，多數程式碼由 Claude Code 與 Codex 協助撰寫；我負責審查、測試與交付，並記錄已測量的結果與尚未驗證的部分。

試用後若發現問題，歡迎在對應的 repository 提交 bug report 或可重現的測試案例。
