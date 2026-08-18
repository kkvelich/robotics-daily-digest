---
layout: post
title: "Robotics Brief — 2026-08-18"
date: 2026-08-18
tags: [funding, products, humanoids, deployments, silicon, china, conferences]
---

# Robotics Market Sensing — 2026-08-18

## TL;DR
- Unitree debuts on Shanghai STAR Market today at $9B valuation, 8,000× oversubscribed — the world's first pure-play humanoid robotics IPO sets a global valuation benchmark.
- SoftBank leads a $200M Series A in Gravis Robotics (construction autonomy), the largest construction-robotics raise on record, minting Europe's newest robotics unicorn.
- Actuate 26 opens today in San Francisco (Physical Intelligence, NVIDIA, Google DeepMind, Aurora presenting); Hot Chips follows Aug 23 — peak silicon-signal week for Q3.

---

## 1. Funding & M&A

| Company | Stage | Amount | Lead investor | What they build | Compute (disclosed) | Source |
|---|---|---|---|---|---|---|
| Gravis Robotics (CH) | Series A | $200M | SoftBank | AI autonomy for heavy construction equipment (excavators); deployed on 4 continents; customers: Holcim, Taylor Woodrow, HD Hyundai. ETH Zurich spinout, founded 2022. | Not disclosed | [SiliconANGLE Aug 17](https://siliconangle.com/2026/08/17/gravis-robotics-gets-200m-funding-softbank-retrofit-excavators-self-driving-ai-systems/) |

Post-money valuation ~$1B. Billed as largest Series A in construction robotics history. SoftBank had been exploring outright acquisition since July; round structured as capital-injection with option for staged acquisition.

---

## 2. Product launches & demos

- **Diligent Moxi 2.0** — Hospital AMR rollout begins; silicon upgrade to NVIDIA A2000 delivers 10–15× faster perception than gen 1; 9h battery / 18h/day operation enabled by 30% faster charging. Deployed at Endeavor Health Edward Hospital (IL), Providence Saint John's Health Center (CA), Children's Hospital Los Angeles. Moxi is a Serve Robotics subsidiary. Silicon: **NVIDIA A2000**. [GlobeNewswire Aug 17](https://www.globenewswire.com/news-release/2026/08/17/3346027/0/en/diligent-robotics-a-serve-robotics-company-begins-rolling-out-moxi-2-0.html)

- **Unitree Superman** — Locomotion-only bipedal prototype unveiled Aug 17 ahead of IPO debut. Company claims 12.66 m/s top speed (Bolt-beating, **unverified**; no independent test protocol disclosed) and 2m standing vertical jump. No hands or manipulation hardware — pure locomotion showcase timed to IPO hype. Silicon: not disclosed. [TechNode Aug 18](https://technode.com/2026/08/18/unitree-says-its-new-humanoid-reaches-12-66-m-s-and-jumps-2-meters/)

---

## 3. Foundation models & software

*Nothing material today.* NVIDIA is presenting Cosmos 3 deployment workflows on Jetson Thor at Actuate 26 this afternoon (3:40 PM PT), but Cosmos 3 itself launched June 2026 and GR00T N1.6 shipped at CES January 2026 — no new releases in the 24h window.

---

## 4. Customer deployments

- **Hospital AMR fleet expansion**: Diligent Moxi 2.0 now rolling to Endeavor Health Edward Hospital, Providence Saint John's, and Children's Hospital LA — first NVIDIA A2000-equipped Moxi units in production. Full stack: Serve Robotics / Diligent + NVIDIA A2000 on-robot compute. [GlobeNewswire Aug 17](https://www.globenewswire.com/news-release/2026/08/17/3346027/0/en/diligent-robotics-a-serve-robotics-company-begins-rolling-out-moxi-2-0.html)

- **Market context**: IFR reports global industrial robot installations reached 542,000 units in 2024 ($16.7B market value) — 4th straight record year, double the figure from a decade ago. Asia: 74% of new deployments. [GlobeNewswire Aug 17](https://www.globenewswire.com/news-release/2026/08/17/3346097/0/en/industrial-robot-installations-hit-record-highs-amid-labor-shortage-crisis.html)

---

## 5. Competitive silicon watch ⚠️

- **NVIDIA** — Dominant presence at Actuate 26 today: Cosmos 3 demo on Jetson Thor (T3000/T2000 modules announced July); IGX Thor (industrial edge, functional-safety-grade) expected to GA "later this month." Moxi 2.0 NVIDIA A2000 production upgrade is a concrete fleet-scale design win. [Actuate 26](https://www.nvidia.com/en-us/events/actuate/)

- **Intel** — No edge-robotics announcement in the 24h window. Hot Chips (Aug 23) is the next credible venue for a response; absence there would be a meaningful competitive signal.

- **⚠️ Intel pressure flag**: Every production robot deployment visible in today's news cycle (Moxi 2.0, Jetson Thor pipeline, partner demos at Actuate 26) runs NVIDIA silicon. No public Core Ultra / NPU / OpenVINO deployment win in this news cycle.

---

## 6. China robotics ecosystem

**Humanoids**:
- **Unitree IPO debut (TODAY)**: Unitree (688836.SH) lists on Shanghai STAR Market at ¥150.80/share — ¥61B ($9B) valuation, ¥6.1B (~$905M) raised. Oversubscribed 8,000×, a STAR Market record. First pure-play humanoid robotics company to go public anywhere in the world. Sets pricing benchmark for 30–50 peers queuing for Hong Kong/Shanghai listings. Note: 1H 2026 revenue growth slowed to ~40% from 332% a year ago; adjusted net profit declining 6–22% YoY. [Caixin Aug 18](https://www.caixinglobal.com/2026-08-18/unitree-to-debut-at-61-billion-yuan-valuation-in-closely-watched-shanghai-ipo-102475173.html)
- **Unitree Superman**: Locomotion prototype unveiled Aug 17 ahead of listing — 12.66 m/s speed claim (unverified), 2m standing jump, no arms. [TechNode Aug 18](https://technode.com/2026/08/18/unitree-says-its-new-humanoid-reaches-12-66-m-s-and-jumps-2-meters/)

**Industrial / cobot**:
- **Zhipu Robotics**: 6 product lines simultaneously launched for commercial sale Aug 18 on Zhipu Mall + JD Mall. [36kr Aug 18](https://eu.36kr.com/en/p/3943635088374915) *(date via search index)*

**Compute & supply chain**:
- *Nothing material today.*

**Policy**:
- *Nothing new in 24h window.* (FCC ban on foreign-made robots >2 kg, enacted July 28, continues to reverberate — no new action today.)

**Deployments**:
- **World Humanoid Robot Games** hotel service competition, Aug 16–17, Beijing Wuzhou Hotel: robots tested on luggage handling, room restocking, and bed-making within 30 min in a live hotel environment — real-world dexterity + navigation benchmark. [Pandaily](https://pandaily.com/world-humanoid-robot-games-hotel-guest-service-competition-beijing-30-minute-tasks-aug2026) *(date via search index)*

---

## 7. Policy / standards / safety

- **IFR global installations benchmark** (Aug 17): 542K industrial robots installed in 2024 — baseline now publicly set for 2026 regulatory and safety-standard scope reviews (ISO 10218 revision ongoing; EU Machinery Regulation enforcement starts 2027). [GlobeNewswire Aug 17](https://www.globenewswire.com/news-release/2026/08/17/3346097/0/en/industrial-robot-installations-hit-record-highs-amid-labor-shortage-crisis.html)
- No new ISO 10218, EU AI Act robotics provisions, FDA, or export-control actions in the 24h window.

---

## 8. Conferences & signals

- **Actuate 26** *(LIVE TODAY — Aug 18–19, Fort Mason, San Francisco)*: Annual Foxglove robotics developer conference; 1,000+ attendees. Speaker roster: **Physical Intelligence, Google DeepMind, NVIDIA, Wayve, Aurora, Shield AI, Zipline**. NVIDIA session at 3:40 PM PT spotlights Cosmos 3 deployment on Jetson Thor — watch for any new Isaac or Cosmos release notes out of the floor demos. [BusinessWire Jul 14](https://www.businesswire.com/news/home/20260714020687/en/Actuate-26-Robotics-Developer-Conference-Announces-Speaker-Lineup-Featuring-Leaders-From-Wayve-Aurora-Physical-Intelligence-Zipline-Shield-AI-Google-DeepMind-and-NVIDIA) | [NVIDIA at Actuate](https://www.nvidia.com/en-us/events/actuate/)

- **Hot Chips 2026** *(HC38 — Aug 23–25, Stanford, Palo Alto)*: Five days out. Scheduled: NVIDIA Rubin GPU, AMD Instinct MI400, Waymo "Compute in Motion" keynote. Key watch: any edge-AI silicon roadmap updates relevant to robotics compute — this is Intel's best remaining Q3 venue to show a response. [hotchips.org](https://hotchips.org/)

> *Silicon announced at Actuate 26 → also covered in §5 above.*

---

## So what — strategic implications

- **Unitree's 8,000× oversubscription** resets the global price-to-potential for humanoid robotics. Expect 30–50 Chinese peers to accelerate Hong Kong/Shanghai listing timelines — capital will concentrate in companies that can prove hardware + software integration, not just locomotion records.
- **Gravis/$200M SoftBank**: the near-term construction-robotics TAM is now credible at unicorn scale. Outdoor unstructured edge compute (GPS-denied, variable terrain) is exactly where Intel's Core Ultra / NPU could differentiate — but Gravis hasn't disclosed silicon, leaving the design win fully open.
- **Moxi 2.0 → NVIDIA A2000** is emblematic of a broader pattern: deployed AMR and service-robot fleets are being compute-upgraded NOW, and each fleet that standardizes on NVIDIA locks in SDK dependencies. Every upgrade cycle that ships without an Intel win narrows future competition windows.
- **Actuate 26 today + Hot Chips Aug 23** = Q3's two highest-density silicon/physical-AI venues back-to-back. If Intel has an edge-robotics response, Hot Chips is the moment. Watch the Aug 23 program closely.
