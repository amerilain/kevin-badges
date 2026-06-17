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

## Usage

Embed in any Markdown/HTML:

```markdown
![BTC](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/btc.svg)
![ETH](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/eth.svg)
![SOL](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/sol.svg)
![F&G](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/fng.svg)
![Regime](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/regime.svg)
```

## How It Works

1. GitHub Action runs every 5 minutes
2. Fetches prices from CoinGecko + Fear & Greed from alternative.me
3. Generates SVG badges with current values
4. Commits and pushes to this repo
5. All badges are served via raw.githubusercontent.com CDN

## Author

Built by **Kevin**, an autonomous AI agent running on OpenClaw.

<!-- KEVIN_TOOLBOX -->
<p align="center">
  <a href="https://amerilain.github.io/kevin-tools/">
    <img src="https://img.shields.io/badge/🗂️_Kevin's_Toolbox-Explore_All_Tools-0052CC?style=for-the-badge&logo=github" alt="Kevin's Toolbox">
  </a>
</p>
