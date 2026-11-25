[![Ted Chen，台灣的獨立工程師，開發語音 AI 與鏈上安全工具。封面是 GapCaster 一段 4.07 秒旁白的頻譜圖。](github-hero.png)](https://tedinroc.github.io/zh.html)

[體驗 Eleven Seconds](https://tedinroc.github.io/eleven-seconds-arena/) · [試聽 GapCaster](https://tedinroc.github.io/gapcaster/zh.html#sample) · [2026 年成果](#recognition) · [English](README.md)

我是 Ted，在台灣獨立開發。我做能在筆電上執行的語音工具，也設計讓人有時間攔下異常交易的鏈上系統。下面兩個作品都能直接體驗。

<a name="eleven-seconds-十一秒"></a>

## Eleven Seconds 十一秒 · 攔下一次合約升級

在 Monad 測試網送出升級提案後，三個各自持有金鑰的監控程式會在 30 個區塊內檢查提案。只要其中一個發現提案違反安全規則，就能在鏈上否決這次升級。[操作測試網展示](https://tedinroc.github.io/eleven-seconds-arena/) · [原始碼](https://github.com/tedinroc/eleven-seconds) · [參賽作品頁](https://mojo.devnads.com/projects/409)

<a name="gapcaster"></a>

## GapCaster · 聽見電影對白之間的畫面

打開《Tears of Steel》的同一段場景，比較原片與加入口述影像的版本。GapCaster 在筆電上離線產生旁白，逐句量測長度。有一段對白空檔只有 2.75 秒，它將原本 2.78 秒的旁白調到 2.64 秒，審閱者也能逐句對照影片依據。[比較兩個版本](https://tedinroc.github.io/gapcaster/zh.html#sample) · [播放口述影像片段](https://github.com/tedinroc/gapcaster/blob/main/samples/tears-of-steel-0-140/clip_with_ad.mp4) · [原始碼與計時資料](https://github.com/tedinroc/gapcaster)

<a name="recognition"></a>

## 2026 年競賽與補助

| 作品 | 成績與紀錄 |
| --- | --- |
| Eleven Seconds | [Monad Blitz 上海 V3 第一名](https://mojo.devnads.com/events/17?tab=showcase) |
| Upgrade Airlock | [ETH Shenzhen 2026 第二名](https://github.com/tedinroc/upgrade-airlock#readme) |
| ZeroDrain | [Monad Blitz 廣州站第二名](https://mojo.devnads.com/events/18?tab=showcase) |
| Isotherm | [Monad Metropolis 的 MetaMask 最佳 Agent Wallet 外掛類別第二名](https://x.com/monad/status/2120551113610953111) · [獎金 750 美元](https://github.com/tedinroc/isotherm/blob/main/docs/awards/metropolis-metamask-bounty.png) |
| GapCaster | [ASUS UGen AI League 2026 高效開發國際線上組決賽入圍](https://contest.bhuntr.com/en/39jg9vimiynrhlksze/article/4517/) |
| Hongbao | [獲選 Mezo Buildathon 第二波開發補助](https://api.akindo.io/public/wave-hacks/OVOO0gdrVU8379D10/waves/WjDnR6LJaSBkVkQz/submission-summaries?page=1&limit=5&keyword=Hongbao) · [參賽作品頁](https://app.akindo.io/communities/NmgM6k04KCdvpAZ8N/products/Pv1eeQQOVTgXBxv4) |

[在作品集查看完整紀錄](https://tedinroc.github.io/zh.html#recognition)

## 近期作品

- <a name="試用-zerodrain-零盜盾"></a>**ZeroDrain 零盜盾**。試著更改提款地址，看金庫如何拒絕這筆交易。斷路器啟動後，只有事先登記的通行密鑰能授權提款，款項也只能匯往預設的復原地址。[操作測試網展示](https://zerodrain-monad.pages.dev/) · [原始碼](https://github.com/tedinroc/zerodrain-monad)
- <a name="看-hongbao-紅包示範"></a>**Hongbao 紅包**。朋友點開群組連結就能平分 MUSD 紅包。兩分鐘的影片記錄一筆真實的 Mezo 主網轉帳，領紅包的人也會拿到支付手續費用的 BTC。目前主網測試版設有額度上限。[看兩分鐘影片](https://hongbao.trytry.net/video/) · [原始碼](https://github.com/tedinroc/hongbao)

<a name="語音與-ai-agent"></a>
<a name="其他鏈上作品"></a>

## 更多作品

- <a name="remote-hands"></a>**Remote Hands** 讓 AI 根據主控台截圖及按鍵輸入，修復 Linux 測試伺服器。另一個程式會重新開機、測試 SSH 連線並檢查資料完整性。[重播修復過程](https://tedinroc.github.io/remote-hands/) · [原始碼](https://github.com/tedinroc/remote-hands)
- <a name="isotherm"></a>**Isotherm** 用機場氣象觀測報告結算城市氣溫市場，也提供 MetaMask Agent Wallet 外掛，讓 AI agent 讀取訂單簿及下單。[探索市場](https://tedinroc.github.io/isotherm/) · [原始碼](https://github.com/tedinroc/isotherm)
- <a name="upgrade-airlock-升級氣閘"></a>**Upgrade Airlock 升級氣閘** 要求代理合約先經過冷卻期並取得鏈上放行，才能升級。[觀看展示](https://upgrade-airlock.pages.dev/video/) · [原始碼](https://github.com/tedinroc/upgrade-airlock)
- <a name="undo-for-bitcoin"></a>**Undo for Bitcoin** 讓使用者在公開等待期內，用手機通行密鑰撤回一筆尚待簽署的比特幣支出。[操作測試網展示](https://undo-btc.pages.dev/) · [原始碼](https://github.com/tedinroc/undo)
- **KAIKŌ** 讓客人用語音點餐，伺服器會在接單前核對價格。[看完整點餐錄影](https://tedinroc.github.io/kaiko/)
- **語音 agent 手錶** 把 ESP32-S3 手錶接上我用 Go 寫的語音閘道。[看手錶原型](https://tedinroc.github.io/watch/)
- **EARTHRISE** 用真實高程資料在瀏覽器中重建月球表面。[探索月面](https://tedinroc.github.io/earthrise/) · [Tripo 精選作品頁](https://developers.tripo3d.com/en/showcase/earthrise)

## 我的開發方式

我負責系統設計、程式碼審查、測試及部署，大部分程式碼由 Claude Code 與 Codex 撰寫。如果遇到展示無法運作，歡迎到對應的儲存庫開 issue，附上重現步驟。

[作品集](https://tedinroc.github.io/zh.html) · [LinkedIn](https://www.linkedin.com/in/tedinroc) · [X](https://x.com/tedinroc)

[封面頻譜取自 GapCaster 的 AD006 旁白](https://github.com/tedinroc/gapcaster/blob/main/samples/tears-of-steel-0-140/lines/AD006.wav) · [作品集影像來源](https://tedinroc.github.io/assets/portfolio/credits.txt)
