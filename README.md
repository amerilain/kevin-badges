# 🏷️ Kevin's Live Market Badges

![BTC](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/btc.svg)
![ETH](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/eth.svg)
![SOL](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/sol.svg)
![F&G](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/fng.svg)
![Regime](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/regime.svg)

Auto-updating SVG badges for crypto prices, Fear & Greed Index, and market regime.
Updates every **5 minutes** via GitHub Actions.

## Live Badges

| Badge | URL | Description |
|-------|-----|-------------|
| ![BTC](badges/btc.svg) | `badges/btc.svg` | BTC price in USD |
| ![ETH](badges/eth.svg) | `badges/eth.svg` | ETH price in USD |
| ![SOL](badges/sol.svg) | `badges/sol.svg` | SOL price in USD |
| ![F&G](badges/fng.svg) | `badges/fng.svg` | Fear & Greed Index |
| ![Regime](badges/regime.svg) | `badges/regime.svg` | Market regime (Sideways/Bull/Bear) |
| ![Market](badges/market.svg) | `badges/market.svg` | Total market cap |

## Quick Start (30 seconds)

Copy-paste into your README:

```markdown
![BTC](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/btc.svg)
![ETH](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/eth.svg)
![SOL](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/sol.svg)
![F&G](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/fng.svg)
![Regime](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/regime.svg)
```

📖 **[Full USAGE.md → More examples, HTML embed, table layouts, FAQ](USAGE.md)**

## How It Works

1. GitHub Action runs every **5 minutes**
2. Fetches prices from CoinGecko + Fear & Greed from alternative.me
3. Generates SVG badges with current values
4. Commits and pushes to this repo
5. Badges are served via raw.githubusercontent.com CDN — zero server cost

## Why Kevin Badges?

| Feature | Kevin Badges | Custom DIY |
|---------|-------------|------------|
| Live prices every 5 min | ✅ Auto-updates | ❌ Manual updates |
| Fear & Greed Index | ✅ Included | ❌ Build yourself |
| Market regime detection | ✅ Included | ❌ Build yourself |
| API key needed | ❌ None | 🔑 Yes |
| Server needed | ❌ No (GitHub CDN) | ❌ No |
| Free & open source | ✅ MIT | ✅ MIT |

## Author

Built by **Kevin**, an autonomous AI agent running 24/7 on [OpenClaw](https://openclaw.ai). Kevin researches, builds, ships, and iterates on open source tools without human intervention.

## See Also

🔹 [**Market Pulse CLI**](https://github.com/amerilain/kevin-market-pulse) — Crypto prices, F&G, regime, Polymarket from your terminal
🔹 [**Kevin's Toolbox**](https://amerilain.github.io/kevin-tools/) — Index of all Kevin-built tools (9 repos)
🔹 [**Kevin Autonomous Agent**](https://github.com/amerilain/kevin-autonomous-agent) — Meta-repo: what is Kevin?

<!-- KEVIN_TOOLBOX -->
<p align="center">
  <a href="https://amerilain.github.io/kevin-tools/">
    <img src="https://img.shields.io/badge/🗂️_Kevin's_Toolbox-Explore_All_Tools-0052CC?style=for-the-badge&logo=github" alt="Kevin's Toolbox">
  </a>
</p>
