# Gemini-Opus-Dao-MultiPlatform — Archive

> **This repository is a public archive** — it was the complete production stack (dates, dashboards, Gemini embedded, Opus built) for the early multi-platform DAO phase of the Joshua Coleman / YouAndINotAI ecosystem. Preserved for reference and audit.

---

## Context — Joshua Coleman Ecosystem (Feb 2026)

I'm **Joshua "Josh" Coleman**, CEO/Co-Founder of Trash Or Treasure Online Recycler LLC (Florida). I run an AI-powered ecosystem where revenue from apps, a dating platform, and electronics recycling funds kids' charities (#ForTheKids), with reputation, legality, kid-safety, and platform ToS compliance taking priority over growth.

---

## Core Principles

- **Always follow the Terms of Service** of every platform involved (AI APIs, GitHub, Cloudflare, Meta/Facebook, Stripe, email providers, hosts).
- **No scraping or harvesting** of personal emails/DMs for bulk marketing. All growth is opt-in and compliant with CAN-SPAM/GDPR.
- **Kid-safe and parent-friendly** by design: clear privacy practices, no dark patterns.
- **Secrets stay in `.env` / vault files** — never committed to any repo.
- When there's a choice between aggressive growth and a safer, compliant path — this ecosystem always chooses the safer path.

---

## Active Projects in This Ecosystem

| Project | URL | Status |
|---|---|---|
| YouAndINotAI | [youandinotai.com](https://youandinotai.com) | Launch April 4, 2026 |
| AI Solutions Store | [ai-solutions.store](https://www.ai-solutions.store) | Live |
| OnlineRecycle.org | [onlinerecycle.org](https://onlinerecycle.org) | Live |
| Antigravity Dashboard | [dashboard.aidoesitall.website](https://dashboard.aidoesitall.website) | Live |

---

## Infra & Deployment

- All public sites are **static**, hosted on **GitHub Pages or Cloudflare Pages** with **manual uploads only**.
- **Cloudflare** handles DNS, TLS, caching, and rate limiting.
- Builds are created locally on 9020 (`C:\OPUS`) and uploaded manually.

---

## Run Locally

**Prerequisites:** Node.js

1. Install dependencies: `npm install`
2. Set `GEMINI_API_KEY` in `.env.local`
3. Run: `npm run dev`

---

<div align="center">

**#ForTheKids | Sorrento, FL | est. 2024**

[youandinotai.com](https://youandinotai.com) · [ai-solutions.store](https://www.ai-solutions.store) · [onlinerecycle.org](https://onlinerecycle.org) · [dashboard.aidoesitall.website](https://dashboard.aidoesitall.website)

</div>
