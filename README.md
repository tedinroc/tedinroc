### Ted Chen

I'm an independent AI engineer in Taiwan. I build voice AI, LLM agents and smart-contract tools on my own. Most of the code is written by Claude Code and Codex: I decide what to build, review everything, test it, deploy it, and run the demos myself.

[中文版](README.zh-TW.md) · [Live demos](https://tedinroc.github.io) · [LinkedIn](https://www.linkedin.com/in/tedinroc)

#### 2026

- **Eleven Seconds** · 1st place at Monad Blitz Shanghai V3 (1st of 39 projects), entered solo. A 30-block cooldown for smart-contract upgrades. Three sentinel processes, each with its own key, attack the new code in simulation and veto it on chain when an invariant breaks. Testnet only.
  [Arena](https://tedinroc.github.io/eleven-seconds-arena/) · [War room](https://tedinroc.github.io/eleven-seconds/) · [Code](https://github.com/tedinroc/eleven-seconds) · [Official results](https://mojo.devnads.com/events/17?tab=showcase)
- **Upgrade Airlock** · 2nd place at ETH Shenzhen 2026, entered solo. Every proxy upgrade has to clear a block cooldown and an on-chain check from a Chainlink CRE workflow that attacks the new implementation in a simulator first. If the attack works, the upgrade gets a signed veto and never runs. Live on Ethereum Sepolia.
  [War room](https://upgrade-airlock.pages.dev/) · [Demo video](https://upgrade-airlock.pages.dev/video/) · [Code](https://github.com/tedinroc/upgrade-airlock)
- **Isotherm** · Monad Metropolis, Track 01 (results pending). Daily temperature strike ladders on Monad testnet. Settlement comes from airport METAR data through a Chainlink CRE workflow. 149 Foundry tests.
  [App](https://tedinroc.github.io/isotherm/) · [Demo video](https://youtu.be/15AFL_xz_3U) · [Code](https://github.com/tedinroc/isotherm)
- **EARTHRISE** · Tripothon S1 entry. Real lunar elevation data and a Tripo-generated Earth, rendered live in three.js.
  [Scene](https://tedinroc.github.io/earthrise/) · [Official entry](https://earthrise-daedalus.pages.dev/)
- **KAIKŌ** · Multi-tenant voice ordering on OpenAI Realtime over WebRTC. When the model misbehaves there's a deterministic Chinese/English fallback, and every tool call is checked server-side.
  [Case study and demo video](https://tedinroc.github.io/kaiko/)
- **ESP32-S3 voice-agent smartwatch** · A voice AI agent on an AMOLED watch, built on xiaozhi-esp32 and ESP-Claw with my own Go voice gateway.
  [Project site (Chinese)](https://tedinroc.github.io/watch/)

Everything here is testnet, demo or prototype work.
