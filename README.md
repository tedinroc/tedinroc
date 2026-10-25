### Ted Chen

Independent AI engineer in Taiwan. I build voice AI, LLM agents and smart-contract tools independently: I define the problem, design the system, direct Claude Code and Codex to produce most of the implementation, then review, test, deploy and demonstrate the result.

[中文版](README.zh-TW.md) · [Live demos](https://tedinroc.github.io) · [LinkedIn](https://www.linkedin.com/in/tedinroc)

#### Selected work, 2026

- **Eleven Seconds** · 1st place at Monad Blitz Shanghai V3 (1st of 39 projects), entered solo. A 30-block cooldown for smart-contract upgrades. Three sentinel processes, each holding its own key, simulate attacks against the new code and veto it on chain when an invariant is violated. Testnet only.
  [Arena](https://tedinroc.github.io/eleven-seconds-arena/) · [War room](https://tedinroc.github.io/eleven-seconds/) · [Code](https://github.com/tedinroc/eleven-seconds) · [Official results](https://mojo.devnads.com/events/17?tab=showcase)
- **Upgrade Airlock** · 2nd place at ETH Shenzhen 2026, entered solo. Every proxy upgrade must pass a block cooldown and obtain on-chain clearance from a Chainlink CRE workflow that first attacks the new implementation in a simulator. An upgrade that fails the attack receives a signed veto and does not execute. Deployed on Ethereum Sepolia.
  [War room](https://upgrade-airlock.pages.dev/) · [Demo video](https://upgrade-airlock.pages.dev/video/) · [Code](https://github.com/tedinroc/upgrade-airlock)
- **Isotherm** · Monad Metropolis, Track 01 (results pending). Daily temperature strike ladders on Monad testnet, with settlement from airport METAR data through a Chainlink CRE workflow. 149 Foundry tests.
  [App](https://tedinroc.github.io/isotherm/) · [Demo video](https://youtu.be/15AFL_xz_3U) · [Code](https://github.com/tedinroc/isotherm)
- **EARTHRISE** · Tripothon S1 entry. Real lunar elevation data and a Tripo-generated Earth, rendered live in three.js.
  [Scene](https://tedinroc.github.io/earthrise/) · [Official entry](https://earthrise-daedalus.pages.dev/)
- **KAIKŌ** · Multi-tenant voice ordering on OpenAI Realtime over WebRTC. A deterministic Chinese/English fallback covers model failure, and every tool call is validated server-side.
  [Case study and demo video](https://tedinroc.github.io/kaiko/)
- **ESP32-S3 voice-agent smartwatch** · A voice AI agent on an AMOLED watch, built on xiaozhi-esp32 and ESP-Claw with an original Go voice gateway.
  [Project site (Chinese)](https://tedinroc.github.io/watch/)

All work here is testnet, demonstration or prototype work.
