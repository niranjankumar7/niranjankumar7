```typescript
const niranjan = {
  role:      "SDET · QA Automation Engineer",
  location:  "Bengaluru, India 🇮🇳",
  stack:     ["Playwright", "TypeScript", "Python", "k6", "Docker"],
  currently: "Building things that break — intentionally.",
};
```

---

## About

I'm an SDET with 4 years across MNCs and startups — I design automation frameworks from scratch, not just write test scripts.

I've owned full test infrastructure end-to-end: framework architecture, CI pipelines, flakiness debugging, performance dashboards, and tooling that makes engineers' lives easier. I also build side projects — trading systems, fintech apps, scrapers — because I learn fastest by shipping.

- 🎭 **Playwright + TypeScript** — primary stack for UI and API automation  
- ⚡ **k6 + Grafana** — performance testing with real dashboards, not CSV exports  
- 🤖 **AI-integrated tooling** — built a PR review agent on Claude API that cuts review cycle time  
- 🐳 **Docker + GitHub Actions** — CI pipelines that run reliably  
- 🐍 **Python** — trading systems, scrapers, data pipelines, and automation  

---

## Projects

### Quality Engineering

| Project | What it does | Stack | State |
|---|---|---|---|
| [automation-cucumber-playwright](https://github.com/niranjankumar7/automation-cucumber-playwright) | BDD E2E framework — validates RudderStack login + event-delivery using UI-to-API hybrid testing | TS · Playwright · Cucumber · GH Actions | ✅ Working |
| [shapes-qa-framework](https://github.com/niranjankumar7/shapes-qa-framework) | Playwright UI regression suite for Shapes web app — explore, search, login flows with POM structure | TS · Playwright | 🔧 In progress |
| [snaptrude-draw-rectangle-tests](https://github.com/niranjankumar7/snaptrude-draw-rectangle-tests) | Canvas interaction automation — draw, resize, delete, undo on Snaptrude's design canvas | TS · Playwright | ✅ Working |
| [performance-test-demo](https://github.com/niranjankumar7/performance-test-demo) | JMeter API performance harness with historical trend tracking, p90/p95 metrics, and CI automation | JMeter · Python · GH Actions | ✅ Working |

### Full-Stack & Products

| Project | What it does | Stack | State |
|---|---|---|---|
| [interview-tracker](https://github.com/niranjankumar7/interview-tracker) | Full-stack prep management app — tracks applications, rounds, sprints, and questions with AI-assisted planning | Next.js · Prisma · Postgres · Zustand | 🔧 In progress |
| crew-savings *(private)* | Rotating savings group platform — crew formation, monthly contributions, auction-based payouts with full transaction accounting | Node/Express · Prisma · React Native · Playwright | ✅ MVP |
| compare-car-price *(private)* | Used-car price meta-search — concurrent multi-source scraping with source reliability dashboard | FastAPI · Celery · Playwright · Next.js | ✅ MVP |

### Trading & Quant Systems

| Project | What it does | Stack | State |
|---|---|---|---|
| trading-algo *(private)* | EMA-based intraday options strategy with backtest + live/paper execution via Kite Connect | Python · Pandas · Kite API | 🧪 Experimental |
| tradingalgoref *(private)* | Modular trading engine — rules/policy/risk/execution layers with shared backtest + live pathway | Python · FastAPI · SQLAlchemy · Kite | 🔧 In progress |
| Insider-bar-candle-trader *(private)* | Insider-bar breakout detector with backtesting, staged exit management, and multi-channel alerts | Python · Pandas · Kite · Telegram | 🔧 In progress |
| Stock-analyst-200ma *(private)* | Daily + weekly scanner for stocks near 200 MA with 30-day breakout/breakdown backtest | Python · yfinance · Pandas | 🧪 Experimental |

> Private repos protect live trading logic and client work — happy to walk through architecture in a conversation.

---

## What I've Shipped That I'm Proud Of

**Rebuilt a broken Cypress suite** into a Playwright framework from scratch — POM, storageState auth, parallel-safe fixtures, 400 scenarios in 6 months, solo. No framework existed before I joined.

**Solved a CI flaky test pattern** caused by a non-deterministic loading spinner. Built a conditional bounded wait (30s max, aligned to product SLA) that handles both "spinner visible" and "spinner never appears" — two separate failure modes from the same test.

**Built a PR review agent** using Claude API that reads diffs and flags issues before human review. Cut review cycle time meaningfully.

**Connected k6 performance tests to Grafana** — replaced CSV exports with live dashboards the team could actually act on.

**Built crew-savings** — full-stack fintech prototype with auction settlement logic, mobile + web clients, and a Playwright API regression suite. Side project built to understand how rotating savings groups work end-to-end.

---

## Tech Stack

**Testing & Automation**  
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-23D96C?style=flat-square&logo=cucumber&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![JMeter](https://img.shields.io/badge/JMeter-D22128?style=flat-square&logo=apachejmeter&logoColor=white)

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Infra & CI**  
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)

**Backend & Data**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

---

## Currently

- 🔭 Learning **contract testing** (Pact) and event-driven test strategies  
- 📚 Grinding **NeetCode 150** daily  
- 📈 Building and backtesting trading systems in Python  
- 🎯 Open to **SDET / QA Automation roles** — let's talk

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN_HERE)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL_HERE)
