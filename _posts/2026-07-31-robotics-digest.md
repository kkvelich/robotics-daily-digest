---
layout: post
title: "Robotics Brief — 2026-07-31"
date: 2026-07-31
tags: [funding, humanoids, foundation-models, deployments, china, policy]
---

# Robotics Market Sensing — 2026-07-31

## TL;DR
- **Gemini Robotics 2** (Google DeepMind, July 30–31): first VLA to control a full humanoid — legs, torso, arms, and multi-finger hands — under a single learned policy; on-device variant runs locally on robot compute.
- **Zoox NHTSA exemption** (July 30): first-ever US federal approval for steering-wheel-free paid robotaxis; 2,500 vehicles/year, Las Vegas launch next month.
- **Unitree STAR Market IPO** (July 30–31): $620M raise at 42B yuan valuation, first humanoid robot A-share listing; China simultaneously threatens retaliation against the US robot import ban.

---

## 1. Funding & M&A

| Company | Stage | Amount | Lead underwriter | What they build | Compute platform | Source |
|---|---|---|---|---|---|---|
| Unitree Robotics (China) | IPO — STAR Market | ¥4.2B (~$620M) | CITIC Securities | Humanoid (G1, H1 Pro) + quadrupeds; #1 global humanoid shipper (5,500+ units in 2025) | Not disclosed | [Caixin, Jul 31](https://www.caixinglobal.com/2026-07-31/robotics-startup-unitree-launches-620-million-star-market-ipo-102469723.html) · [Xinhua, Jul 31](https://english.news.cn/20260731/20953e97618041788ceb70d7ee451a02/c.html) |

Pricing inquiry August 5; subscriptions open August 10. Prospectus issued July 30 evening, kicking off the A-share issuance process. Proceeds earmarked for AI model R&D, robot-body development, and a smart-manufacturing base. Forbes called it "the first public robot valuation benchmark." [Forbes, Jul 30](https://www.forbes.com/sites/jonmarkman/2026/07/30/unitrees-ipo-will-set-the-first-public-robot-valuation-benchmark/)

---

## 2. Product launches & demos

*Nothing material today.*

---

## 3. Foundation models & software

- **Gemini Robotics 2** (Google DeepMind, July 30–31) — Three models shipped together:
  - *Gemini Robotics 2*: VLM + VLA; first DeepMind model to control a complete humanoid (legs → fingertips) under one learned policy checkpoint. Runs across three hardware configs: Apptronik Apollo 2 with SharpaWave hands, Apollo 2 with Inspire hands, and Franka Duo bi-arm + Robotiq gripper.
  - *Gemini Robotics On-Device 2*: optimized VLA that runs locally on robotic hardware; adapts to new embodiments with only a few hours of training data. On-device chip target not publicly specified.
  - *Multi-robot collaboration model*: coordinates two or more robots for joint manipulation tasks.
  - Demonstrated tasks: trash removal, watering-can placement, tape insertion, lightbulb screwing, garbage-bag tying. DeepMind frames this as a milestone toward "physical AGI."
  - Sources: [MarkTechPost, Jul 30](https://www.marktechpost.com/2026/07/30/google-deepmind-gemini-robotics-2-whole-body-control-dexterity-multi-robot-collaboration/) · [Dataconomy, Jul 31](https://dataconomy.com/2026/07/31/gemini-robotics-2-gives-robots-full-body-ai-control/) · [Robotics & Automation News, Jul 31](https://roboticsandautomationnews.com/2026/07/31/google-deepmind-unveils-gemini-robotics-2-as-apptronik-humanoid-demonstrates-whole-body-ai/103802/) · [DeepMind blog](https://deepmind.google/blog/gemini-robotics-2-brings-whole-body-intelligence-to-robots/)

---

## 4. Customer deployments

- **Zoox (Amazon)** — NHTSA issued a formal commercial exemption from 8 FMVSS standards (steering wheels, pedals, rear-view mirrors, windshield defrost, vehicle braking systems, others), effective July 31, 2026–July 31, 2028. Authorizes up to 2,500 new vehicles per year. Paid rides launching Las Vegas next month; SF, Austin, Miami, LA, and Atlanta to follow as state/local approvals land. Vehicle specs: electric, bidirectional, 4 inward-facing seats, 75 mph top speed, zero manual controls. First-ever US commercial exemption for a purpose-built (not converted) autonomous vehicle. [TechCrunch, Jul 30](https://techcrunch.com/2026/07/30/zoox-clears-final-federal-hurdle-to-launch-paid-robotaxi-service/) · [Federal Register, Jul 31](https://www.federalregister.gov/documents/2026/07/31/2026-15485/zoox-grant-of-temporary-exemption-from-portions-of-various-requirements-of-the-federal-motor-vehicle) · [Carrier Management, Jul 30](https://www.carriermanagement.com/news/2026/07/30/290564.htm)

---

## 5. Competitive silicon watch ⚠️

- **LG Electronics Q2 2026** (results released July 30, widely reported July 31): LG named NVIDIA as a deepening strategic partner across robotics, AI factories, and mobility. AIDC cooling orders exceeded ₩600B in H1 after NVIDIA certification for CDU models; several trillion won targeted by year-end. A new robotics business center is now operational with an actuator pilot line. Intel not mentioned in LG's robotics roadmap. [LG Newsroom](https://www.lg.com/global/newsroom/news/corporate/lg-electronics-releases-second-quarter-2026-financial-results/) · [Digitimes, Jul 31](https://www.digitimes.com/news/a20260731VL202/lg-electronics-robotics-infrastructure-lg-sales.html) (date via search index)

⚠️ **Intel pressure note**: No Intel-branded compute appears in any of today's major stories. Gemini Robotics On-Device 2's hardware target is unspecified — a competitive opening if NVIDIA Jetson Thor or Qualcomm RB-series claims a reference integration first.

---

## 6. China robotics ecosystem

- **Humanoids**: Unitree launches STAR Market IPO (July 30–31) — see Section 1. At ¥1.699B 2025 revenue and 60.1% gross margin on core business, the listing creates China's first public humanoid valuation anchor. [TechNode, Jul 31](https://technode.com/2026/07/31/unitree-robotics-moves-closer-to-shanghai-star-market-ipo/)

- **Industrial / cobot**: *Nothing new today.*

- **Compute & supply chain**: *Nothing new today.*

- **Policy**: China's commerce ministry issued a sharp statement July 30 threatening to "resolutely retaliate" if the US maintains its FCC-enacted ban on new Chinese humanoid and quadruped robot imports (ban announced July 28 by Trump administration on national-security grounds, effective immediately for new model authorizations). Ministry called the action a "new provocation" that "severely damages" bilateral trade relations, accused the US of discrimination and suppression of Chinese companies, and demanded immediate withdrawal. [CNBC, Jul 30](https://www.cnbc.com/2026/07/30/china-us-robot-humanoid-ban-trump-visit.html) · [DNYUZ, Jul 30](https://dnyuz.com/2026/07/30/china-threatens-retaliation-as-u-s-moves-to-block-robot-imports/)

- **Deployments**: *Nothing new today.*

---

## 7. Policy / standards / safety

- **NHTSA Zoox Exemption** (Federal Register, effective Jul 31): First commercial FMVSS exemption for a purpose-built AV. Sets a precedent for future AMR/delivery-robot operators seeking similar carve-outs from safety standards written for human-driven vehicles. [Federal Register](https://www.federalregister.gov/documents/2026/07/31/2026-15485/zoox-grant-of-temporary-exemption-from-portions-of-various-requirements-of-the-federal-motor-vehicle)

- **US-China robot trade escalation** (Jul 30): China's retaliation threat against the US FCC robot import ban raises supply-chain risk for US operators using Chinese components (actuators, LiDAR, compute). Unresolved; watch for Chinese countermeasures targeting US tech exports.

---

## 8. Conferences & signals

*Nothing material today from major robotics or silicon/edge-AI events.*

---

## So what — strategic implications

1. **Gemini Robotics 2 resets the VLA competitive map.** Whole-body control from a single policy checkpoint is the new target. The on-device variant's unspecified compute target is the critical unknown: whichever silicon vendor secures the reference integration (Jetson Thor, Qualcomm RB-series, or Core Ultra) gains a key design-win narrative. Intel should move fast to claim GR2-On-Device on OpenVINO.

2. **Zoox sets the regulatory template for autonomous mobile systems.** NHTSA granting a commercial exemption for a purpose-built platform — not a converted car — gives future indoor/outdoor AMR and delivery-robot operators a regulatory pathway to cite. Watch for follow-on petitions from sidewalk robot and warehouse AGV players.

3. **Unitree IPO creates the first public humanoid valuation benchmark.** At 42B yuan implied valuation with strong gross margins, every private humanoid startup and VC portfolio gets re-priced. China's supply-chain scale (90%+ of global humanoid shipments) now has a public ledger.

4. **US-China robot decoupling is entering a new phase.** FCC import ban + China retaliation threat = robotics hardware supply chains now explicitly in the trade-war frame. For US edge-AI deployments dependent on Chinese actuators or LiDAR, supply-chain diversification moves from strategic planning to operational urgency. Intel's domestic silicon angle strengthens in this context if marketed correctly.
