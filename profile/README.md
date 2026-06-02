<div align="center">

<a href="https://www.exogen.app/en">
  <img src="https://raw.githubusercontent.com/ExogenCorporation/.github/main/profile/assets/banner.png" alt="Exogen" width="100%" />
</a>

<br/>

**The intersection of AI and blockchain: automated crypto trading, built for everyone.**

<br/>

[![Website](https://img.shields.io/badge/Website-exogen.app-F4B860?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0A0B10)](https://www.exogen.app/en)
[![Status](https://img.shields.io/badge/Status-In_Active_Development-2ea043?style=for-the-badge&labelColor=0A0B10)](https://github.com/ExogenCorporation)
[![Contact](https://img.shields.io/badge/Contact-exogen@exogen.app-F4B860?style=for-the-badge&logo=maildotru&logoColor=white&labelColor=0A0B10)](mailto:exogen@exogen.app)

</div>

---

## About Exogen

**Exogen** is an AI-powered crypto trading platform that turns complex market strategy into something anyone can run. The platform pairs a high-performance quantitative engine with an intuitive web dashboard. Backtest a strategy, deploy a bot, and manage funds across major exchanges from a single interface.

We build at the boundary of **artificial intelligence** and **blockchain**: machine-assisted strategy execution on one side, on-chain and exchange connectivity on the other.

<br/>

## What's Inside

<table>
<tr>
<td width="50%" valign="top">

**Trading & Automation**
- Real-time trading dashboard
- Automated bot strategy execution
- Strategy backtesting & simulation
- Advanced funds management

</td>
<td width="50%" valign="top">

**Platform & Experience**
- Multi-language support (i18n)
- Dark / light themes
- Built-in tax reporting
- Security-first account model

</td>
</tr>
</table>

<br/>

## Architecture

Exogen ships as a single [`exogen-monorepo`](https://github.com/ExogenCorporation/exogen-monorepo). One platform, cleanly separated into a web app, backend services, a quant engine, and deploy tooling.

| Path | Stack | Role |
| :--- | :--- | :--- |
| `frontend/` | Next.js · TypeScript | Web dashboard & trading interface |
| `services/api-client/` | Node.js | Public-facing API gateway |
| `services/api-private/` | Node.js | Core private backend services |
| `services/bot-exec/` | Python · C++ | Strategy execution engine |
| `apps/backtester/` | C++ · Qt / QML | Backtesting & market simulation |
| `deploy/` | Docker · Kubernetes | Infrastructure & deployment orchestration |

> The [`exogen-monorepo`](https://github.com/ExogenCorporation/exogen-monorepo) is private and accessible to authorized team members only.

<br/>

## Tech Stack

<div align="center">

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Ethers.js](https://img.shields.io/badge/Ethers.js-2535A0?style=for-the-badge&logo=ethereum&logoColor=white)

**Backend & Quant Engine**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Qt](https://img.shields.io/badge/Qt_/_QML-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes_(k3s)-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

<br/>

## Markets & Integrations

<div align="center">

**Exchanges**

![Binance](https://img.shields.io/badge/Binance-F3BA2F?style=for-the-badge&logo=binance&logoColor=black)
![dYdX](https://img.shields.io/badge/dYdX-6966FF?style=for-the-badge&logoColor=white)
![Hyperliquid](https://img.shields.io/badge/Hyperliquid-50D2C2?style=for-the-badge&logoColor=black)

**Assets**

![Bitcoin](https://img.shields.io/badge/Bitcoin-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
![Solana](https://img.shields.io/badge/Solana-9945FF?style=for-the-badge&logo=solana&logoColor=white)
![Cardano](https://img.shields.io/badge/Cardano-0033AD?style=for-the-badge&logo=cardano&logoColor=white)
![Polkadot](https://img.shields.io/badge/Polkadot-E6007A?style=for-the-badge&logo=polkadot&logoColor=white)
![USDC](https://img.shields.io/badge/USDC-2775CA?style=for-the-badge&logo=circle&logoColor=white)

</div>

<br/>

---

<div align="center">

<img src="https://raw.githubusercontent.com/ExogenCorporation/.github/main/profile/assets/small-logo.png" alt="Exogen" width="44" />

**Building the future at the intersection of AI and blockchain.**

[exogen.app](https://www.exogen.app/en) · [exogen@exogen.app](mailto:exogen@exogen.app)

</div>
