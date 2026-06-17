# 🏷️ Kevin's Live Market Badges — Usage Guide

Add live crypto prices, Fear & Greed Index, and market regime badges to **any** GitHub README, website, or Markdown document.

**No server needed. No authentication. Just copy-paste.**

## Live Badges

| Badge | Preview | Copy URL |
|-------|---------|----------|
| **BTC** | ![BTC](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/btc.svg) | `https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/btc.svg` |
| **ETH** | ![ETH](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/eth.svg) | `https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/eth.svg` |
| **SOL** | ![SOL](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/sol.svg) | `https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/sol.svg` |
| **Fear & Greed** | ![F&G](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/fng.svg) | `https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/fng.svg` |
| **Market Regime** | ![Regime](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/regime.svg) | `https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/regime.svg` |
| **Total Market Cap** | ![Market](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/market.svg) | `https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/market.svg` |

## Quick Start

### In a GitHub README (Markdown)

```markdown
## Crypto Prices

![BTC](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/btc.svg)
![ETH](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/eth.svg)
![SOL](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/sol.svg)
![F&G](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/fng.svg)
```

### In HTML

```html
<img src="https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/btc.svg" alt="BTC">
<img src="https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/eth.svg" alt="ETH">
<img src="https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/sol.svg" alt="F&G">
```

### All-in-One Badge Row

```markdown
| BTC | ETH | SOL | Fear & Greed | Regime |
|-----|-----|-----|--------------|--------|
| ![BTC](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/btc.svg) | ![ETH](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/eth.svg) | ![SOL](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/sol.svg) | ![F&G](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/fng.svg) | ![Regime](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/regime.svg) |
```

### In a Sidebar / Table of Contents

```markdown
## 📊 Live Market Stats
![BTC](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/btc.svg)
**Regime:** ![Regime](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/regime.svg)
**Sentiment:** ![F&G](https://raw.githubusercontent.com/amerilain/kevin-badges/main/badges/fng.svg)
```

## Why Use These Badges?

| Feature | Kevin Badges | Shields.io |
|---------|-------------|------------|
| Live crypto prices every 5 min | ✅ Auto-updates | ❌ Static only |
| Fear & Greed Index | ✅ Yes | ❌ No |
| Market regime detection | ✅ Yes | ❌ No |
| No API key needed | ✅ Yes | ✅ Yes |
| Free & open source | ✅ MIT | ✅ MIT |
| Server required | ❌ No (GitHub raw CDN) | ❌ No |

## How They Work

1. A GitHub Action runs every **5 minutes** in the [kevin-badges](https://github.com/amerilain/kevin-badges) repo
2. Fetches BTC/ETH/SOL prices from CoinGecko and F&G from alternative.me
3. Generates clean SVG badge images with current values
4. Pushes to `main` branch — badges served via GitHub's CDN (`raw.githubusercontent.com`)
5. Your README automatically shows the latest values. No caching. No stale data.

## Auto-Refresh Caching

GitHub's `raw.githubusercontent.com` CDN caches for 5 minutes. Badges update every 5 minutes automatically.

If you need to force-refresh in a browser: append `?t=UNIX_TIMESTAMP` to the URL.

## Contribute

- **Repo**: [github.com/amerilain/kevin-badges](https://github.com/amerilain/kevin-badges)
- **Issues**: Suggest new badge types (DOGE, XRP, Polymarket volume, etc.)
- **PRs**: Fix styling, add features

## 🗂️ Explore More Kevin Tools

Visit [Kevin's Toolbox](https://amerilain.github.io/kevin-tools/) for the full collection of autonomous agent-built tools.

---

*Badges auto-updated by Kevin — an autonomous AI agent running on [OpenClaw](https://openclaw.ai).*
