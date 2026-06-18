---
layout: post
title: "Robotics Brief — 2026-06-18"
date: 2026-06-18
tags: [products, humanoids, deployments, silicon, china, conferences]
---

# Robotics Market Sensing — 2026-06-18

## TL;DR
- **Foxconn makes its European humanoid debut at VivaTech Paris** (June 17), running a closed-loop NVIDIA Isaac GR00T stack on its assembly robot — and formalizes a Vera Rubin NVL72 production partnership with Bull in France.
- **Autonomique crosses pilot → production** at F&P Mfg., a Tier-1 auto supplier: one of the first confirmed physical-AI live-line deployments in a North American factory.
- **Automate 2026 pre-show ramp**: NVIDIA-sponsored Humanoid Pavilion (22–25 Jun, Chicago) locks in 20+ humanoids; Richtech DEX confirmed as featured exhibitor with Isaac Sim Sim2Real stack.

---

## 1. Funding & M&A

*Nothing material today.*

---

## 2. Product Launches & Demos

- **Foxconn wheeled humanoid at VivaTech (Paris)** — First European public demo of Foxconn's industrial assembly humanoid. Robot performs dual-arm precision tasks; trained via NVIDIA Isaac GR00T + Sim2Real; runs on-robot embodied intelligence derived from actual factory scenarios. Foxconn also showed Vera Rubin NVL72, HGX, and MGX platforms on the booth. Silicon: **NVIDIA Isaac GR00T / Jetson stack** (implied; Vera Rubin NVL72 for datacenter-side training). [(date via search index) TechTimes June 17](https://www.techtimes.com/articles/318548/20260617/foxconn-debuts-humanoid-robots-europe-revealing-closed-loop-physical-ai-stack.htm)

- **Richtech Robotics DEX** — Selected as featured exhibitor in the first-ever NVIDIA-sponsored Humanoid Pavilion at Automate 2026 (Chicago, June 22–25). Will demo two DEX units: one doing laser-engraving for live give-aways, one running an interactive guided presentation. Silicon: **NVIDIA** (Isaac Sim Sim2Real training pipeline, on-robot). [(date via search index) GlobeNewsWire June 17](https://www.globenewswire.com/news-release/2026/06/17/3313360/0/en/Richtech-Robotics-Selected-as-Featured-Exhibitor-in-First-Ever-Humanoid-Pavilion-at-Automate-2026.html)

---

## 3. Foundation Models & Software

*Nothing material today.*

---

## 4. Customer Deployments

- **Autonomique → F&P Mfg. (F.tech TYO:7212, Canada)** — Bi-manual wheeled robot completed a paid pilot doing precision multi-part assembly of automotive chassis and suspension components; now advancing to live production line. Strategic partnership targets global rollout across F.tech's international factory network. Compute platform: not disclosed. [(date via search index) The Robot Report June 17](https://www.therobotreport.com/autonomique-deploys-semi-humanoid-robots-canadian-tier-1/) | [PRNewswire](https://www.prnewswire.com/news-releases/autonomique-advances-semi-humanoid-robots-to-production-deployment-at-tier-1-automotive-supplier-fp-mfg-302803092.html)

---

## 5. Competitive Silicon Watch ⚠️

**NVIDIA tightening grip on European factory AI (pressure on Intel's edge-robotics position):**

- **Foxconn + NVIDIA + Bull (Atos/Eviden) manufacturing partnership** — Components for the **Vera Rubin NVL72** platform will be built at Foxconn's Czech Republic facilities, then assembled and fully validated at Bull's factory in Angers, France. Commercially shipped under the Bull brand. This formalizes a vertically integrated supply chain where Foxconn manufactures the very GPU racks used to *train* its factory humanoids. Loop: Vera Rubin trains Isaac GR00T → GR00T runs the assembly robot → robot generates training data. [(date via search index) PRNewswire / Morningstar June 17](https://www.prnewswire.com/news-releases/hon-hai-technology-group-foxconn-accelerates-global-leadership-in-ai-factories-infrastructure-at-europes-vivatech-302802796.html)

**⚠️ Intel flag:** Zero Intel silicon visible in today's announcements. NVIDIA Isaac GR00T is the named stack for both Foxconn's factory humanoids and Richtech DEX. Intel Core Ultra Series 3 robotics positioning (announced at Computex) has not surfaced at VivaTech or in the Automate pre-show news cycle. European factory AI is consolidating around NVIDIA's full stack.

---

## 6. China Robotics Ecosystem

- **Humanoids — AGIBOT at VivaTech 2026** — Shanghai's AGIBOT (Zhiyuan) is exhibiting its full embodied AI portfolio at VivaTech (June 17–20, Paris), with live demonstrations covering interaction, locomotion, manipulation, and multi-robot coordination. First major European trade-show appearance; signaling active outreach to European industrial buyers. [AGIBOT newsroom](https://www.agibot.com/article/231/detail/78.html)

- **Humanoids — HABS + Unitree live telepathy demo at VivaTech** — French neurotech firm HABS is running a live brain-computer-interface-to-humanoid demo using a Unitree robot at VivaTech, billed as a "world premiere." Unitree providing the humanoid body; non-invasive Neuro-AI controlling it. Signals Unitree's active European ecosystem-building.

- **Industrial / cobot:** *Nothing confirmed in the 24h window.*

- **Compute & supply chain:** *Nothing confirmed in the 24h window.*

- **Policy:** *Nothing confirmed in the 24h window.*

- **Deployments:** AGIBOT and Unitree are the named China players at VivaTech Paris this week; European customer conversations are live on the floor.

---

## 7. Policy / Standards / Safety

*Nothing material today.*

---

## 8. Conferences & Signals

**VivaTech 2026** (Paris Expo Porte de Versailles, June 17–20 — **live now**):
- Jensen Huang delivering the GTC Paris keynote within the June 17–20 window; themes: AI factories, agentic AI, physical AI. Watch for any new product or partnership drops.
- Foxconn European humanoid debut (Section 2 + Section 5).
- AGIBOT + Unitree/HABS on the floor (Section 6).
- Euronews frames the event as "Foxconn and NVIDIA bet big on France as Europe's AI hub." [(date via search index) Euronews June 18](https://www.euronews.com/next/2026/06/18/from-foxconn-to-nvidia-why-france-is-so-attractive-for-europes-ai-infrastructure)

**Automate 2026** (McCormick Place, Chicago, June 22–25 — opens in 4 days):
- NVIDIA-sponsored Humanoid Robot Pavilion: 20+ humanoid robots and orgs confirmed; free to all attendees; dedicated theater for continuous demos.
- Richtech DEX confirmed (Section 2).
- Humanoid Robot Forum: paid track running Tuesday–Wednesday.
- **Watch:** This is the highest-signal North American show for physical AI deployments and partnership announcements this half of 2026.

---

## So What — Strategic Implications

- **NVIDIA's physical-AI moat in Europe is being poured today.** The Foxconn-Bull-NVIDIA Vera Rubin manufacturing loop is more than a supply-chain deal — it ties European AI factory infrastructure to NVIDIA compute *and* Isaac GR00T as the software layer. Any European OEM that buys into this stack is also adopting NVIDIA's robotics platform. Intel has no analogous integrated offer on the floor at VivaTech.

- **Pilot-to-production is the new funding headline.** Autonomique at F&P Mfg. is the story type that will multiply through H2 2026 — named Tier-1 customer, real production line, global expansion planned. Compute platform was not disclosed; worth tracking whether physical-AI software plays like Autonomique default to NVIDIA or remain silicon-agnostic.

- **Automate 2026 (June 22–25) is 4 days away — prepare for a barrage.** 50,000+ attendees, NVIDIA-sponsored pavilion with 20+ humanoids, pre-show news already ramping. Set a digest alert for June 22; expect humanoid deployments, partnership announcements, and cobot platform reveals.

- **Chinese humanoids are marketing in Paris, not just manufacturing.** AGIBOT's live European demos and Unitree's VivaTech telepathy stunt are deliberate customer-acquisition moves, not tech showcases. If European buyers engage, Chinese suppliers will have the cost and volume advantages to close. This is a direct competitive threat to Western humanoid makers with longer timelines to mass production.
