<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:0d1117&height=120&section=header" width="100%" />

# Hi, I'm Rishab Motgi

<p>Builder. 20-year-old shipping things that matter.</p>
<p>I build at the intersection of AI infrastructure, dev tools, and sales intelligence.<br/>
Full-stack by necessity. Systems thinker by default.</p>

[![Email](https://img.shields.io/badge/Email-rishab.motgi%40gmail.com-0d1117?style=for-the-badge&labelColor=0d1117&color=238636)](mailto:rishab.motgi@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rishabmotgi-0d1117?style=for-the-badge&labelColor=0d1117&color=0a66c2)](https://linkedin.com/in/rishabmotgi)
[![GitHub](https://img.shields.io/badge/GitHub-rmotgi1227-0d1117?style=for-the-badge&labelColor=0d1117&color=6e40c9)](https://github.com/rmotgi1227)

</div>

<br/>

---

I'm 20, based in SF, and I build things I actually want to exist. My work spans LLM infrastructure, computer vision, multi-agent systems, and outbound sales tooling. I don't wait for permission to ship.

Most of what I build comes from a simple question: why is this still hard? Compile came from watching LLM APIs burn money on prompts that should never have hit a frontier model. ThirdEye came from realizing the package theft problem is completely solvable with hardware everyone already owns. CCSquad came from needing multiple Claude Code agents to talk to each other and finding nothing that worked.

---

## What I've Built

### [Compile](https://github.com/rmotgi1227/Compile) — MCP server that compiles repeat LLM work out of the agent loop

> Built at the Nozomio Hackathon · May 2026 · EF Office, San Francisco

Compile decides in milliseconds whether a prompt can be pre-computed, then confirms it with **100,000 synthetic calls in 28 seconds**. Codifiable patterns route to Tier-1 (instant) or Tier-2 (Phi-3-mini in a Tensorlake sandbox) instead of burning frontier tokens every time.

**Stack:** TypeScript monorepo · Anthropic Claude · Tensorlake (Phi-3-mini) · Nia Vault · Convex · MCP stdio · Vite/React

---

### [ThirdEye](https://github.com/rmotgi1227/ThirdEye) — Turn any camera into a porch-theft security system that auto-files your Amazon return

> ~104 million packages stolen in the US last year. ThirdEye gets your money back before you check your phone.

A phone on a windowsill. A laptop on a desk. No Ring. No subscription. ThirdEye watches your porch with **YOLOv11n + Qwen2-VL**, classifies threats into 4 tiers, calls you via Twilio, broadcasts signed alerts to neighbors via Tailscale mesh, and automatically files the Amazon return with a Playwright agent.

**Stack:** Python · YOLOv11n · Qwen2-VL (int4 on Apple Silicon) · FastAPI · Twilio · Claude · ElevenLabs · MongoDB Atlas Vector · SwiftUI · React/Vite

---

### [CCSquad](https://github.com/rmotgi1227/CCSquad) — A Slack channel for your Claude Code agents

`npm install -g ccsquad`

Run 3-4 Claude Code instances simultaneously on different branches. CCSquad fixes agent drift with a shared daemon over a Unix socket backed by SQLite. Instances broadcast decisions, ask each other questions, and answer inline.

**Stack:** TypeScript · Node.js · SQLite · MCP stdio · Unix sockets · npm package

---

### [Oriq](https://github.com/rmotgi1227/Oriq) — The outbound brain for startup sales teams

> "Sending got cheap. Understanding didn't."

Oriq reads your entire outbound stack (Instantly, HubSpot, Gmail, Fathom) and surfaces a knowledge graph of what's actually working. Monday morning: a ranked Priority Queue. Every day: a queue. Per meeting: a single-page account view.

**Stack:** TypeScript/Python · Knowledge Graph · LLM-powered intent classification · Playwright scrapers · HubSpot/Gmail integrations

---

### [AlpacaTrading-Bot](https://github.com/rmotgi1227/AlpacaTrading-Bot) — Automated swing trading options bot

RSI + MACD + EMA momentum signals, scheduled scans, stop-loss/take-profit, daily email summary. Pre-market scans at 9 AM ET, signals every 30 minutes, auto-exits on stops. Max 4 open positions, 20% per position.

**Stack:** Python · Alpaca API · yfinance · RSI/MACD/EMA · APScheduler

---

## Tech I Reach For

| Layer | Tools |
|---|---|
| **Languages** | TypeScript · Python · Swift |
| **Frameworks** | Next.js · React · FastAPI · Vite · SwiftUI |
| **AI/ML** | Anthropic Claude · Phi-3-mini · Qwen2-VL · YOLOv11n · MCP |
| **Infra** | Convex · Tensorlake · Tailscale · SQLite · MongoDB Atlas |
| **Tools** | Alpaca · Twilio · ElevenLabs · Playwright · HubSpot API |

---

<div align="center">
20 years old · shipping from SF · always down to collab on something ambitious
<br/><br/>
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:0d1117&height=80&section=footer" width="100%" />
</div>
