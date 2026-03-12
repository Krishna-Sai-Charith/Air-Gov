# 🏙️ AirGov — Delhi Infrastructure Monitor

> A real-time urban infrastructure governance dashboard for Delhi NCR — tracking construction projects, air quality violations, multi-agency approvals, and AI-powered conflict detection across the city.

---

## 🌫️ The Problem

Delhi's construction boom is fragmented across dozens of agencies — DPCC, NHAI, DMC, DMRC, PWD, Delhi Jal Board — with no unified visibility. Overlapping projects compound AQI spikes, approvals get stuck in silos, and violations go undetected until they become crises.

**AirGov fixes that.**

---

## 🗺️ What It Does

| Feature | Description |
|--------|-------------|
| 🗺️ **Live Map** | Leaflet-powered interactive map of Delhi NCR with all active construction sites |
| 🌡️ **AQI Monitoring** | Per-site air quality index with PM2.5, PM10, NO₂, CO, SO₂ and Ozone readings |
| 📋 **Project Dashboard** | 14 real infrastructure projects across Delhi — road works, metro, sewage, industrial, solar |
| 🔄 **Approval Workflows** | 5-stage multi-agency clearance tracker (DMC → DPCC → Traffic → Waste → Final) |
| 🚨 **Alerts System** | Critical, warning, and info alerts for violations, overdue approvals, and conflicts |
| 🤖 **AI Assessment** | Per-project risk, conflict, and action analysis with compound AQI detection |
| 👤 **Role Switcher** | View the dashboard as Field Officer, DPCC Analyst, Senior Officer, or Admin |
| 🗂️ **Layer Controls** | Toggle construction sites, AQI zones, traffic impact, and sensitive locations |

---

## 🚦 Project Status Types

- 🔴 **Critical** — Violation flagged, DPCC rejected, or AQI at dangerous levels
- 🟡 **Under Review** — Awaiting agency clearance or monitoring
- 🟢 **On Schedule** — Fully approved and progressing normally
- 🔵 **Pending Start** — Approved, not yet begun

---

## 🏗️ Projects Covered

Projects span 6 districts and 6 categories:

| Icon | Category |
|------|----------|
| 🛣️ | Road Works |
| 🚇 | Underground / Metro |
| 🏭 | Industrial |
| 🔧 | Sewage & Utilities |
| ♻️ | Waste Processing |
| ⚡ | Construction / Energy |

Notable projects include NH-48 Flyover Expansion, Metro Phase IV Janakpuri, Rohini Industrial Retrofit, ITO Bridge Restoration, Narela Solar Park, and Connaught Place Underground Cable.

---

## 🤖 AI Conflict Detection

AirGov's AI layer flags compound risks that agencies can't see in isolation:

- **Zone Conflicts** — Multiple construction sites within 1–2km triggering combined AQI spikes
- **Approval Bottlenecks** — Overdue multi-agency clearances blocking downstream work
- **Sensitive Site Proximity** — Automatic alerts when projects are near schools, hospitals, or nature reserves
- **Compound AQI** — Calculates additive pollution from overlapping zones (e.g. Dwarka Triple Zone: +87 pts)

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| 🗺️ Maps | [Leaflet.js](https://leafletjs.com/) v1.9.4 |
| 🎨 UI | Vanilla HTML/CSS/JS — zero framework dependencies |
| 🔤 Fonts | [Syne](https://fonts.google.com/specimen/Syne) (headings) + [Inter](https://fonts.google.com/specimen/Inter) (body) |
| 📦 Deployment | Single-file — no build step required |

---

## 👥 Role-Based Views

Switch roles in the top-right dropdown to see how different officials interact with the same data:

| Role | Actions Available |
|------|------------------|
| 🟢 Field Officer | Submit field report, Flag issue |
| 🔵 DPCC Analyst | Approve clearance, Request data |
| 🟡 Senior Officer | Escalate, Override |
| 🔴 Admin | Full access |

---

## 📍 Coverage Area

**Delhi NCR** — 28.61°N 77.21°E

Districts: Dwarka · West Delhi · Rohini · Shahdara · Central Delhi · North Delhi · South Delhi · South East Delhi · North West Delhi

Connected agencies: **DDA · NHAI · DPCC · DMRC**

---

## 📄 License

MIT — free to use, adapt, and deploy.

---

*Built to make Delhi's infrastructure governance transparent, accountable, and data-driven.* 🏙️
