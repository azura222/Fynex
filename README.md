# Fynex

Simple investing, diversified returns. A DeFi portfolio platform on Base.

Fynex lets users create diversified yield-generating portfolios ("stashes") across multiple vaults on the Base blockchain. Pick a strategy, deposit any token, and start earning.

## Features

- **Vault Strategies** — Three yield vaults (yoUSD, yoETH, yoBTC) with preset or custom allocations
- **PDF Reports** — Export portfolio summary with allocation breakdown and transaction history
- **PWA** — Installable as a native app on mobile

## Tech Stack

| Layer | Tech |
|-------|------|
| Framework | Nuxt 4 / Vue 3 / TypeScript |
| Styling | Tailwind CSS 4 + shadcn-vue |
| Web3 | Viem + Wagmi |
| Auth | Privy  |
| PDF | jsPDF |

### Fund Presets

| Strategy | Risk | yoUSD | yoETH | yoBTC |
|----------|------|-------|-------|-------|
| Conservative | Low | 50% | 25% | 25% |
| Balanced | Medium | 35% | 35% | 30% |
| Aggressive | High | 10% | 45% | 45% |


### Install & Run

```bash
npm install
npm run dev
```

### Build

```bash
npm run build
npm run preview
```

