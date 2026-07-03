# SPOXY

### 🎯 The PvP Battleground For Predictions

*Create, join, and compete in prediction challenges — powered by Solana*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](CONTRIBUTING.md)
[![Made with HTML5](https://img.shields.io/badge/Made%20with-HTML5-orange.svg?style=for-the-badge&logo=html5)](index.html)
[![X / Twitter](https://img.shields.io/badge/X-@Spoxy__dev-black?style=for-the-badge&logo=x)](https://x.com/Spoxy_dev)
[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/XgXmFyghs)

[🌐 Live Site](#-quick-start) · [🐛 Report Bug](.github/ISSUE_TEMPLATE/bug_report.md) · [💡 Request Feature](.github/ISSUE_TEMPLATE/feature_request.md) · [📖 Docs](docs/)

---

## 📌 About SPOXY

SPOXY is a peer-to-peer prediction battleground built on Solana. Instead of betting against a house, users create or join **challenges** — head-to-head prediction markets on crypto prices, sports outcomes, or anything else — and the reward pool is settled automatically once the outcome resolves.

| Feature | Description |
|---|---|
| ⚔️ **Pure PvP** | Every challenge is player vs player — your win is someone else's loss, no house edge |
| 🔗 **On-chain settlement** | Crypto markets resolve automatically via price oracles |
| 🗳️ **Community governance** | Sports & off-chain markets verified by SPOXY Masters NFT holders |
| ⚡ **Instant payouts** | Reward pools distribute automatically to winners, no manual claims |
| 🔓 **No gatekeeping** | Connect a Solana wallet and go — no sign-up forms, no KYC |

---

## 🚀 Quick Start

### Option 1 — Open Directly

Just open `index.html` in any modern browser. It's a static, single-file landing page — no build step required.

### Option 2 — Clone & Serve Locally

```bash
# Clone the repository
git clone https://github.com/<your-username>/spoxy.git
cd spoxy

# Serve locally (any static server works)
python3 -m http.server 8080
# then visit http://localhost:8080
```

### Option 3 — Deploy

The site is a static page, so it deploys as-is to GitHub Pages, Vercel, Netlify, or Cloudflare Pages — point the deploy at `index.html` and you're live.

---

## 🗂️ Project Structure

```
spoxy/
├── .github/
│   └── ISSUE_TEMPLATE/
│       ├── bug_report.md
│       └── feature_request.md
├── assets/              # images, fonts, static media (add as needed)
├── docs/
│   └── getting-started.md
├── .gitignore
├── .nojekyll
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── README.md
└── index.html           # the landing page
```

---

## 📖 How It Works

1. **Connect Your Wallet** — link a Solana wallet (e.g. Phantom) and deposit funds.
2. **Create a Challenge** — pick a market, set the condition, timeframe, and stake collateral.
3. **Join a Battle** — browse open challenges and stake on the side you believe in.
4. **Resolution** — crypto markets settle via price oracles; other markets via NFT-holder voting.
5. **Payout** — winners are paid out automatically, no claims process.

See [docs/getting-started.md](docs/getting-started.md) for the full walkthrough.

---

## 🤝 Contributing

Contributions are welcome, from fixing a typo to shipping a new section.

1. **Fork** this repository
2. **Create** your branch: `git checkout -b feat/your-feature`
3. **Commit**: `git commit -m 'feat: add X'`
4. **Push**: `git push origin feat/your-feature`
5. **Open a Pull Request**

Read the full [Contributing Guide →](CONTRIBUTING.md)

---

## 📄 License

Licensed under the [MIT License](LICENSE).

---

**⭐ If you like SPOXY, consider starring the repo!**

Made with ❤️ · [X / Twitter](https://x.com/Spoxy_dev) · [Discord](https://discord.gg/XgXmFyghs)
