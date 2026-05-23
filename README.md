# CivicPulse AI — Public Services Command Centre

> AI-powered incident triage and coordination for mass events, medical camps, and public services

![CivicPulse](https://img.shields.io/badge/CivicPulse-v2.5.0-D4A017?style=flat-square)
![Status](https://img.shields.io/badge/status-live-22C55E?style=flat-square)

---

## What is CivicPulse?

CivicPulse gives public service coordinators **AI-powered decision support in under 2 seconds** — so the right action reaches the right place, every time.

Mass events and emergency services generate hundreds of incidents that coordinators must triage instantly. Today this happens with radios, paper forms, and gut instinct. CivicPulse changes that.

**Built by a first-year Mechanical Engineering student at the University of Doha for Science and Technology.**

---

## Live Demo

🔗 **[civicpulse.vercel.app](https://civicpulse.vercel.app)**

Hit **"Watch live simulation"** on the welcome screen — no setup needed.

---

## Features

### Command Centre
- **Live incident feed** — real-time incoming incidents with severity classification
- **AI triage analysis** — instant action plans, resource recommendations, escalation paths
- **Interactive map** — zone-based incident visualisation with blip animations
- **Action queue** — confirm, escalate, and resolve incidents with full audit trail
- **Auto-escalation** — critical incidents unactioned for 5+ minutes escalate automatically

### Intelligence
- **AI insight panel** — pattern detection across session activity
- **Shift handover brief** — AI-generated summary for incoming coordinators
- **Session log** — full timestamped audit trail, exportable as .txt

### Operations
- **Analytics dashboard** — live charts updating with real session data
- **Field report builder** — formal incident documentation with PDF export
- **Responsible AI framework** — transparent risk identification and mitigations

### Experience
- **Live ticker** — scrolling incoming incident feed
- **Simulation mode** — auto-runs 3 scenarios, perfect for demos
- **Coordinator profile** — personalised command identity
- **Two themes** — Black/Gold (default) and Parchment
- **Keyboard shortcuts** — 1–6 switch tabs, S run simulation, Esc close
- **localStorage persistence** — queue and log survive page refresh
- **Sound feedback** — subtle audio on analysis, escalation, resolve

---

## Responsible AI

CivicPulse is built with responsible AI at its core:

| Risk | Level | Mitigation |
|------|-------|------------|
| Algorithmic bias | CRITICAL | Every output labelled advisory; human confirmation required |
| Over-reliance | CRITICAL | AI never auto-dispatches; human-in-loop enforced by design |
| Data privacy | HIGH | No personal identifiers in AI prompts; role-based anonymisation |
| Language barriers | MEDIUM | Arabic support on v3 roadmap; handles non-native English |
| Connectivity dependency | MEDIUM | Core functions work offline; paper fallback provided |
| Accountability | LOW | Full timestamped audit log with export |

---

## Tech Stack

- **Frontend:** Vanilla HTML/CSS/JavaScript — zero dependencies
- **AI:** Claude Sonnet (smart demo mode — works without API key)
- **Fonts:** Space Grotesk, Space Mono, Bebas Neue via Google Fonts
- **Deployment:** Vercel (static hosting)
- **Storage:** localStorage for session persistence

---

## Deploy in 10 Minutes

### Option 1 — Vercel (recommended)

1. Fork this repo
2. Go to [vercel.com](https://vercel.com) → New Project → Import your fork
3. Leave all settings default → Deploy
4. Your URL: `civicpulse-[yourname].vercel.app`

### Option 2 — GitHub Pages

1. Go to repo Settings → Pages
2. Source: Deploy from branch → main → / (root)
3. Your URL: `[username].github.io/civicpulse`

### Option 3 — Local

```bash
git clone https://github.com/[your-username]/civicpulse
cd civicpulse
open index.html
```

No build step. No npm install. Just open the file.

---

## Project Structure

```
civicpulse/
└── index.html          # Entire application — single file
└── README.md           # This file
```

---

## Incident Types Supported

Medical · Crowd · Fire · Infrastructure · Security · Other

Each type has dedicated AI response templates covering CRITICAL, HIGH, MEDIUM, and LOW severity scenarios — crowd crush, heat emergencies, mass casualties, power failures, missing persons, and more.

---

## Roadmap

- [ ] Arabic language support (v3)
- [ ] Real-time multi-coordinator sync
- [ ] Live API integration with optional key
- [ ] Mobile-optimised view
- [ ] Historical incident database

---

## About the Builder

First-year Mechanical Engineering student at **UDST — University of Doha for Science and Technology**, Qatar.

Volunteered at FIFA World Cup Qatar 2022, FIFA Arab Cup Qatar 2025, and Asian Medical Camps Qatar. CivicPulse is built from firsthand experience of how coordinators operate under pressure at mass events.

Previous projects: [FactoryOS](https://factoryonline-production.up.railway.app/) · [PredictiveMaintenance AI](https://predictivemaintenance-91fu.onrender.com/login) · [MechSim](https://mechsim.onrender.com/)

---

*Built for the USAII Global AI Hackathon 2026 · Public Services track*
