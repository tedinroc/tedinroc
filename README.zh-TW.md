[![Ted Chen，台灣的獨立工程師](github-hero.png)](https://tedinroc.github.io/zh.html)

[作品集](https://tedinroc.github.io/zh.html) · [LinkedIn](https://www.linkedin.com/in/tedinroc) · [X](https://x.com/tedinroc) · [English](README.md)

我在台灣獨立開發語音工具和鏈上應用。

## [試用 ZeroDrain 零盜盾](https://zerodrain-monad.pages.dev/)

在 Monad 測試網竄改提款地址，看金庫攔下這筆交易。斷路器啟動後，只有事前登記的通行密鑰能授權提款，款項只能匯往預設的復原地址。

[Monad Blitz 廣州站第二名](https://mojo.devnads.com/events/18?tab=showcase) · [原始碼](https://github.com/tedinroc/zerodrain-monad)

## [看 Hongbao 紅包示範](https://hongbao.trytry.net/video/)

兩分鐘的影片記錄了一個在 Mezo 主網發出的 MUSD 紅包。朋友點開群組連結就能平分紅包，原本沒有錢包也能領。每份紅包預設存入收款人的儲蓄帳戶，另附少量 BTC 支付手續費。目前主網測試版設有額度上限。

[獲選 Mezo Buildathon 第二波補助](https://app.akindo.io/communities/NmgM6k04KCdvpAZ8N/products/Pv1eeQQOVTgXBxv4) · [原始碼](https://github.com/tedinroc/hongbao)

## 語音與 AI agent

- <a name="gapcaster"></a>**GapCaster** 在筆電上離線產生口述影像，量過旁白的實際長度，再改寫或調速，讓它剛好落在電影對白的空檔。每句描述都留有依據，方便對照影片審閱。**入圍 ASUS UGen AI League 2026 決賽。** [看加入口述影像的片段](https://github.com/tedinroc/gapcaster/blob/main/samples/tears-of-steel-0-140/clip_with_ad.mp4) · [程式碼與輸出範例](https://github.com/tedinroc/gapcaster)
- <a name="remote-hands"></a>**Remote Hands** 讓 AI 根據主控台截圖及按鍵輸入，修復 Linux 測試伺服器。另一個程式會重新開機、測試 SSH 連線，並檢查資料完整性。 [重播修復過程](https://tedinroc.github.io/remote-hands/) · [原始碼](https://github.com/tedinroc/remote-hands)
- **KAIKŌ** 讓客人用語音點餐，伺服器在接單前會核對價格並驗證工具呼叫。 [看完整點餐錄影](https://tedinroc.github.io/kaiko/)
- **語音 agent 手錶** 把 ESP32-S3 手錶接上我用 Go 寫的語音閘道。 [看手錶原型](https://tedinroc.github.io/watch/)

## 其他鏈上作品

- <a name="eleven-seconds-十一秒"></a>**Eleven Seconds 十一秒** 讓三個獨立監控程式在 30 個區塊的等待期內檢查合約升級，並能在鏈上否決違規操作。**Monad Blitz 上海 V3 第一名。** [操作測試網展示](https://tedinroc.github.io/eleven-seconds-arena/) · [原始碼](https://github.com/tedinroc/eleven-seconds) · [官方得獎名單](https://mojo.devnads.com/events/17?tab=showcase)
- <a name="upgrade-airlock-升級氣閘"></a>**Upgrade Airlock 升級氣閘** 要求代理合約先經過冷卻期並取得鏈上放行，才能升級。**ETH Shenzhen 2026 第二名。** [觀看展示](https://upgrade-airlock.pages.dev/video/) · [原始碼](https://github.com/tedinroc/upgrade-airlock)
- <a name="isotherm"></a>**Isotherm** 用機場氣象觀測報告結算城市氣溫市場，並提供 MetaMask Agent Wallet 外掛，讓 AI agent 使用訂單簿。**獲 Monad Metropolis 的 MetaMask 賞金 US$750。** [探索專案](https://tedinroc.github.io/isotherm/) · [原始碼](https://github.com/tedinroc/isotherm) · [得獎紀錄](https://github.com/tedinroc/isotherm/blob/main/docs/awards/metropolis-metamask-bounty.png)
- <a name="undo-for-bitcoin"></a>**Undo for Bitcoin** 讓使用者能在公開等待期內，用手機的通行密鑰撤回尚待簽署的比特幣支出。 [操作測試網展示](https://undo-btc.pages.dev/) · [原始碼](https://github.com/tedinroc/undo)

系統由我設計，大部分程式碼由 Claude Code 與 Codex 撰寫。我負責審查、測試與部署。如果展示出錯，歡迎在對應的儲存庫開 issue，附上重現步驟。

我也用真實高程資料做了一個 three.js 月球場景。 [探索 EARTHRISE](https://tedinroc.github.io/earthrise/) · [作品集影像來源](https://tedinroc.github.io/assets/portfolio/credits.txt)
