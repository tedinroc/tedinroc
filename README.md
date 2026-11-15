[![Ted Chen — Independent AI engineer in Taiwan.](assets/profile-hero.png)](https://tedinroc.github.io/)

Independent AI engineer in Taiwan. I build **voice AI, agents and onchain safety tools**.

**[Explore the portfolio](https://tedinroc.github.io/)** · [LinkedIn](https://www.linkedin.com/in/tedinroc) · [X](https://x.com/tedinroc) · [繁體中文](README.zh-TW.md)

## Selected work

[GapCaster](#gapcaster) · [Remote&nbsp;Hands](#remote-hands) · [Undo](#undo-for-bitcoin) · [Eleven&nbsp;Seconds](#eleven-seconds) · [Airlock](#upgrade-airlock) · [Isotherm](#isotherm)

### GapCaster

[![GapCaster — offline audio description fitted to dialogue gaps. Open the sample.](assets/projects/gapcaster.png)](https://github.com/tedinroc/gapcaster/blob/main/samples/tears-of-steel-0-140/clip_with_ad.mp4)

Offline audio description: generate a line, measure its spoken duration, then adjust or rewrite it to fit the dialogue gap. Each line keeps its evidence for human review.

Laptop prototype · **ASUS UGen AI League 2026 finalist**

[Watch the sample](https://github.com/tedinroc/gapcaster/blob/main/samples/tears-of-steel-0-140/clip_with_ad.mp4) · [Sample outputs](https://github.com/tedinroc/gapcaster/tree/main/samples/tears-of-steel-0-140) · [Source code](https://github.com/tedinroc/gapcaster)

### Remote Hands

[![Remote Hands — console repair with independent verification. Open the recorded replay.](assets/projects/remote-hands.png)](https://tedinroc.github.io/remote-hands/)

An AI agent repairs Linux test servers from console screenshots and keystrokes. A separate probe checks the result: reboot, SSH and data integrity.

Controlled test prototype

[Replay the repair](https://tedinroc.github.io/remote-hands/) · [Film](https://youtu.be/1kL6B0gGCck) · [Source code](https://github.com/tedinroc/remote-hands)

### Undo for Bitcoin

[![Undo for Bitcoin — cancel a pending signing request with a passkey. Open the testnet demo.](assets/projects/undo.png)](https://undo-btc.pages.dev/)

Bitcoin spends enter a public waiting period before NEAR Chain Signatures supplies the second signature. A phone passkey cancels pending requests; a cold key recovers funds after a Bitcoin timelock.

NEAR testnet + Mutinynet

[Watch the demo](https://undo-btc.pages.dev/) · [Source code](https://github.com/tedinroc/undo) · [Verification guide](https://github.com/tedinroc/undo#run-it)

### Eleven Seconds

[![Eleven Seconds — simulate attacks and veto rule-breaking upgrades. Open the Monad testnet arena.](assets/projects/eleven-seconds.png)](https://tedinroc.github.io/eleven-seconds-arena/)

During a 30-block upgrade cooldown, three independently keyed sentinels simulate attacks and veto rule violations onchain. An AI reporter explains the result; the veto follows deterministic rules.

Monad testnet · **1st place, Monad Blitz Shanghai V3** · Solo

[Try the attack cards](https://tedinroc.github.io/eleven-seconds-arena/) · [Source code](https://github.com/tedinroc/eleven-seconds) · [Official results](https://mojo.devnads.com/events/17?tab=showcase)

### Upgrade Airlock

[![Upgrade Airlock — a cooldown and clearance before contract upgrades. Watch the Sepolia demo.](assets/projects/upgrade-airlock.png)](https://upgrade-airlock.pages.dev/video/)

Proxy upgrades need a cooldown and onchain clearance. A Chainlink CRE workflow simulates attacks, then broadcasts clearance or veto through the CRE CLI simulator.

Sepolia testnet · **2nd place, ETH Shenzhen 2026** · Solo

[Watch the demo](https://upgrade-airlock.pages.dev/video/) · [War room](https://upgrade-airlock.pages.dev/) · [Source code](https://github.com/tedinroc/upgrade-airlock)

### Isotherm

[![Isotherm — city-temperature markets with agent access. Explore the Monad testnet project.](assets/projects/isotherm.png)](https://tedinroc.github.io/isotherm/)

City-temperature markets with one Kuru order book per strike, settlement from airport METAR reports, and a MetaMask Agent Wallet plugin for trading agents.

Monad testnet · **MetaMask bounty winner, Monad Metropolis — US$750**

[Explore the project](https://tedinroc.github.io/isotherm/) · [Demo film](https://youtu.be/15AFL_xz_3U) · [Source code](https://github.com/tedinroc/isotherm) · [Award](https://github.com/tedinroc/isotherm/blob/main/docs/awards/metropolis-metamask-bounty.png)

## More experiments

- **[KAIKŌ](https://tedinroc.github.io/kaiko/)** — Voice ordering with server-validated tool calls and prices; a recorded demo-store order.
- **[Voice-agent watch](https://tedinroc.github.io/watch/)** — An ESP32-S3 prototype built on xiaozhi-esp32 and ESP-Claw, with my own Go voice gateway.
- **[EARTHRISE](https://tedinroc.github.io/earthrise/)** — A three.js lunar scene using real elevation data and a Tripo-generated Earth.

## How I work

I design the systems. Claude Code and Codex write most of the code; I review it, run the tests and deploy it. Each repository records the measurements and remaining limitations.

Bug reports with a reproduction are welcome in the project repositories.

[Image credits](https://tedinroc.github.io/assets/portfolio/credits.txt)
