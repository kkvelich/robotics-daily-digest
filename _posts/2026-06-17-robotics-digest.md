---
layout: post
title: "Robotics Brief — 2026-06-17"
date: 2026-06-17
tags: [products, humanoids, conferences]
---

# Robotics Market Sensing — 2026-06-17

## TL;DR
- Faraday Future unveiled its EAI robotics lineup last night (June 16) — Futurist humanoid, FX Aegis quadruped, FF Master Mini and FF Nova teasers — with **native NVIDIA SONIC whole-body control** integration; low-credibility vendor but SONIC adoption outside NVIDIA's own partners is a real signal.
- **HITEC 2026 exhibit floor closes today** (San Antonio, June 15–18): Richtech ADAM dual-arm service robot running live cocktail demos; hospitality is proving a near-term deployment beachhead.
- **Automate 2026** (Chicago, June 22–25) is 5 days out — NVIDIA-sponsored Humanoid Robot Pavilion is the nearest high-signal industrial venue; the battle for the industrial compute narrative starts next week.

---

## 1. Funding & M&A

*Nothing material today.*

---

## 2. Product launches & demos

- **Faraday Future EAI Robotics lineup (launched June 16)** — Event at LA HQ, 5:30 PM PDT. Confirmed products: **FF Futurist** full-size humanoid (from $34,990), **FF Master** athletic humanoid (from $19,990), **FX Aegis** quadruped security/companion (from $2,490). Teasers: FF Master Mini and FF Nova. Key platform claim: first U.S. full-size humanoid with native **NVIDIA SONIC** whole-body motion control (open 42M-param model, released Feb 2026). Open-source "EAI Brain" + decentralized data factory strategy, targeting B2C education market. Silicon: NVIDIA SONIC motion layer confirmed; broader inference stack undisclosed. ⚠️ FF (NASDAQ: FFAI) is financially distressed — flag delivery timelines as speculative. [BusinessWire](https://www.businesswire.com/news/home/20260611380179/en/Faraday-Future-Announces-the-Launch-of-Its-EAI-Robotics-Education-Ecosystem-Strategy-Product-Line-New-EAI-Device-Launch-being-held-on-June-16-2026) · [SONIC model detail](https://rits.shanghai.nyu.edu/ai/nvidia-open-sources-sonic-a-foundation-model-for-humanoid-whole-body-control/)

- **Richtech Robotics ADAM @ HITEC 2026 (Day 3 today)** — Dual-arm AI beverage/food service robot, live cocktail demos at Booth #3224, San Antonio. DUST-E S autonomous floor cleaner also on exhibit. Exhibit hall closes tonight. Compute: undisclosed. [GlobeNewswire](https://www.globenewswire.com/news-release/2026/06/12/3311082/0/en/Richtech-Robotics-to-Showcase-Dual-Armed-AI-Powered-ADAM-and-DUST-E-S-Autonomous-Cleaning-Robots-at-HITEC-2026.html)

---

## 3. Foundation models & software

*Nothing material today.*

---

## 4. Customer deployments

*Nothing material today.*

---

## 5. Competitive silicon watch ⚠️

*Nothing material today.*

> **Intel baseline (Computex, June 2–5):** Intel Robotics (newly named division) announced the OpenVINO Physical AI Framework and logged 130+ Core Ultra Series 3 design engagements for edge robotics — including a live Ella bartender demo running three concurrent AI agents on-chip. This is the current competitive baseline. Automate 2026 is the next major data point for Intel's position.

---

## 6. China robotics ecosystem

- **Humanoids**: *Nothing material today.*
- **Industrial / cobot**: *Nothing material today.*
- **Compute & supply chain**: *Nothing material today.*
- **Policy**: *Nothing material today.*
- **Deployments**: *Nothing material today.*

---

## 7. Policy / standards / safety

*Nothing material today.*

---

## 8. Conferences & signals

| Event | Dates | Location | Status | Key signal |
|-------|-------|----------|--------|------------|
| **HITEC 2026** | June 15–18 | San Antonio, TX | **LIVE — last floor day** | Richtech ADAM/DUST-E S demos; exhibit closes tonight |
| **Automate 2026** | June 22–25 | Chicago, IL | 5 days out | NVIDIA-sponsored Humanoid Robot Pavilion; Humanoid Forum; ~50K attendees |

- **HITEC 2026 (Day 3, closing tonight):** Richtech ADAM is running live demos — constrained-task food/beverage service robots are past the "proof of concept" gate in hospitality. Current compute requirement is modest (vision + manipulation inference). The upgrade cycle to NPU-class edge workloads begins when multi-modal voice + vision reasoning layers are added (Richtech's SoundHound voice integration roadmap is the near-term signal). [HITEC 2026](https://www.hitec.org/)

- **Automate 2026 signal positioning:** NVIDIA is sponsoring the first dedicated Humanoid Robot Pavilion in McCormick Place's North Building — the AI/software hub — directly in front of 50K industrial decision-makers. Exhibitor pre-show press briefings typically drop June 18–20; those announcements are the highest-signal preview of which silicon platforms are in production humanoids and AMRs. [Automate Humanoid Pavilion](https://www.automateshow.com/education-networking/humanoid-robot-pavilion) · [Embedded Computing Design](https://embeddedcomputing.com/application/industrial/automation-robotics/nvidia-sponsors-new-humanoid-robot-pavilion-at-automate-2026)

---

## So what — strategic implications

- **NVIDIA SONIC's open-model strategy is working.** Even a marginal player like Faraday Future cites native SONIC integration as a primary differentiator. Open-sourcing a 42M-param whole-body controller in February seeded adoption across the long tail of humanoid builders and locks them into NVIDIA's GR00T/Isaac evaluation stack. Intel has no equivalent open motion-control model — the white space in the software layer is widening.

- **Automate 2026 is Intel's most actionable near-term venue.** The NVIDIA-sponsored Humanoid Pavilion will define the industrial humanoid compute narrative for 50K buyers. Intel Robotics (named division since Computex) needs a visible Core Ultra + OpenVINO Physical AI story on the Automate floor. Pre-show announcement window is June 18–20 — monitor for Intel partner announcements and any Qualcomm RB-series AMR integrations from exhibitors.

- **Hospitality is a developing edge compute beachhead.** HITEC confirms service robots are scaling in real hotel deployments. Today's inference load is lightweight; multi-modal reasoning (voice + vision + navigation) will upgrade the workload to NPU-class within 12–18 months. Developing hospitality channel partnerships now positions for that compute upsell.

- **Tomorrow's watch list:** Post-event FFAI coverage and any silicon partner disclosure from the June 16 stream · Automate 2026 exhibitor pre-announcements (June 18–20) · arXiv cs.RO new submissions overnight.
