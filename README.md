# 🤖 RestRevive AI

> Restaurant operations intelligence platform.

[![Status](https://img.shields.io/badge/status-beta%20pilot-brightgreen)](#)
[![Stack](https://img.shields.io/badge/stack-React%2018%20%2B%20Supabase-blue)](#)
[![License](https://img.shields.io/badge/license-MIT-green)](#)

---

## Overview

RestRevive AI is a restaurant operations intelligence platform that analyzes operational data and delivers AI-driven insights to help restaurant operators reduce costs, improve efficiency, and make better decisions faster.

Currently in **active beta pilot at Seasons Bar & Grill**.

## Features

- 📊 **Operations Analysis** — AI-powered diagnostics across labor, food cost, and service
- 🔍 **Anomaly Detection** — flags unusual patterns in sales, waste, and staffing
- 📊 **Performance Dashboards** — real-time KPIs with trend visualization
- 🤖 **AI Recommendations** — actionable suggestions powered by Anthropic Claude
- 🔔 **Alerts** — threshold-based notifications for critical metrics

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React 18 |
| Backend | Supabase |
| AI Engine | Anthropic API (Claude) |
| Auth | Supabase Auth |

## Getting Started

```bash
git clone https://github.com/ShadowWalkerNC/RestRevive-AI.git
cd RestRevive-AI
npm install
npm run dev
```

Create a `.env.local` file:
```
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_anon_key
VITE_ANTHROPIC_API_KEY=your_anthropic_key
```

## Status

- [x] Repository initialized
- [x] Beta pilot — Seasons Bar & Grill
- [ ] Multi-location support
- [ ] Public launch

## Related

- [CulinaryOS](https://github.com/ShadowWalkerNC/CulinaryOS) — companion kitchen management platform

---

*Built by [ShadowWalkerNC](https://github.com/ShadowWalkerNC)*
