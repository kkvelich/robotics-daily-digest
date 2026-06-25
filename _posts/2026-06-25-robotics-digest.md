---
layout: post
title: "Robotics Brief — 2026-06-25"
date: 2026-06-25
tags: [funding, humanoids, products, silicon, china, conferences]
---

# Robotics Market Sensing — 2026-06-25

## TL;DR
- **Agility Robotics announced a $2.5B SPAC merger** with Churchill Capital Corp XI on June 24 — humanoid robotics' first major IPO vehicle, $620M in proceeds, Foxconn leading the PIPE, Digit v5 on NVIDIA IGX Thor.
- **Morgan Stanley doubled its 2026 China humanoid shipment forecast to 50,000 units** (from 28,000), declaring the industry has entered "early commercialization" — driven by a $1B State Grid order and Robotera deploying at SF Express and China Post.
- **Automate 2026 closes today** (Chicago, June 22–25): NVIDIA Halos safety system, ABB Physical AI Toolchain, and Kawasaki's first 8-DOF robot were the defining show-floor moves — and the largest automation show in 50 years wrapped with humanoid deployment displacing humanoid demo as the dominant discourse.

---

## 1. Funding & M&A

| Company | Stage | Amount | Lead investor | What they build | Compute platform | Source |
|---|---|---|---|---|---|---|
| Agility Robotics | SPAC / IPO | $2.5B valuation; $620M gross proceeds ($420M SPAC trust + $200M PIPE) | Foxconn (PIPE lead); existing: DCVC, NVIDIA, Amazon, SoftBank Vision Fund 2 | Digit bipedal humanoid for warehouses, logistics, manufacturing | NVIDIA IGX Thor + Halos Core | [TechCrunch](https://techcrunch.com/2026/06/24/agility-robotics-plans-to-go-public-via-spac-in-a-2-5b-deal/) |

**Key details:** Merger with Churchill Capital Corp XI; ticker "AGLT" on a major North American exchange; 9 commercial sites, 65,000+ operational hours. Close expected H2 2026, subject to shareholder vote and SEC review. Announcement timed to last day of Automate 2026. [The Robot Report](https://www.therobotreport.com/humanoid-maker-agility-robotics-go-public-through-spac-merger/)

---

## 2. Product launches & demos

Automate 2026 (McCormick Place, Chicago — final day today) was the stage for multiple debuts:

- **Kawasaki RL030N** — Industry's first 8-DOF (8-axis) robot built for physical AI. Additional axis adds dexterity for confined spaces; open KRNX real-time API enables direct ROS, ML, and vision-system control. Also premiered: MXP360L and BA013L industrial robots. Silicon: not specified; architecture is ROS-compatible. [Kawasaki Robotics](https://kawasakirobotics.com/news/kawasaki-robotics-unveils-dexterous-physical-ai-robot-platform-advanced-automation-technologies-at-automate-2026/) (date via search index)

- **ABB Physical AI Toolchain** — Show debut of ABB's full software stack for industrial robot AI: data generation → training/validation → deployment. Paired with new **PoWa high-speed cobot family** and Aura Sensae capacitive-sensing integration. Backed by ABB's March 2026 NVIDIA partnership (RobotStudio HyperReality for sim-to-real). Silicon: NVIDIA (sim/training side). [Robotics 24/7](https://www.robotics247.com/article/automate-2026-abb-robotics-delivers-new-industry-ready-physical-ai) (date via search index)

- **Kawasaki + Dexterity collaboration** — Expanded partnership to scale physical AI for warehouse logistics, announced at Automate June 23. [RoboticsTomorrow](https://www.roboticstomorrow.com/news/2026/06/23/kawasaki-robotics-and-dexterity-expand-collaboration-to-scale-physical-ai-for-warehouse-logistics/26767) (date via search index)

---

## 3. Foundation models & robotics software

*Nothing with a confirmed June 24–25 release date.*

**Background context (June 22, Automate):** NVIDIA **Halos for Robotics** is the company's safety-software layer — Halos OS + Holoscan Sensor Bridge — running on IGX Thor. It is not a VLA/world-model, but it is the safety-certification software that locks robot OEMs to NVIDIA compute. Agility Digit v5 is the first adopter. See Section 5 for the competitive read.

---

## 4. Customer deployments

*No new named-customer production-rollout announced in the strict 24h window.*

**From Agility SPAC filing (June 24 context):** Digit currently operating across 9 commercial sites with 65,000+ hours — customers include Amazon, GXO, Schaeffler, and Toyota Motor Manufacturing Canada (Woodstock, Ontario; 7 units, RaaS model). [Agility Robotics](https://www.agilityrobotics.com/content/agility-robotics-to-go-public-through-merger-with-churchill-capital-corp-xi)

---

## 5. Competitive silicon watch ⚠️

**NVIDIA — Halos for Robotics (Automate 2026, June 22)** ⚠️ *Pressures Intel edge-robotics position*

NVIDIA announced [Halos for Robotics](https://nvidianews.nvidia.com/news/nvidia-announces-halos-for-robotics-the-industrys-first-full-stack-safety-system-for-physical-ai) — described as the industry's first full-stack safety system for physical AI, drawing on 18,600+ engineering years of AV safety development. Stack: **NVIDIA IGX Thor** (compute), Holoscan Sensor Bridge (sensor fusion), Halos OS (safety runtime), and an ANAB-accredited AI Systems Inspection Lab for certification support. Agility Digit v5 is Launch Partner 1. FORT Robotics is the first safety-framework integrator (Outside-In Safety Blueprint). (date via search index)

⚠️ **Intel pressure analysis:** Halos is architected around IGX Thor, not Intel hardware. The safety certification layer is a high-value lock-in stratum: once a robot OEM builds and certifies against Halos, swapping underlying compute becomes an expensive re-certification exercise. Intel has no equivalent certified safety stack for humanoids or cobots. This is platform-moat building at the compliance layer — a dimension where compute TFLOPS don't compete directly.

**No new Qualcomm, Ambarella, Hailo, Rockchip, or MediaTek announcements confirmed in the 24h window.**

---

## 6. China robotics ecosystem

- **Humanoids — Market forecast:** Morgan Stanley upgraded its 2026 China humanoid shipment estimate for the **second time this year** to **50,000 units** (Jan est: 14,000 → revised to 28,000 → now 50,000). 2030 projection: 446,000 units, $15B market (106% CAGR from 2025). Key trigger: industry officially entered "early commercialization" phase. [CNBC, June 24](https://www.cnbc.com/2026/06/24/morgan-stanley-china-humanoid-robot-market-forecast.html)

- **Deployments:** State Grid Corporation placed a **¥6.8B (~$1B) procurement order** covering ~8,500 robots (500 humanoids, 3,000 dual-arm, 5,000 quadrupeds) — the single largest embodied-AI anchor order on record. SF Express and China Post are now running **Robotera** humanoids at logistics centers for sorting/handling; Robotera reports 300%+ Q2 2026 growth and began thousand-unit deliveries. [CNBC](https://www.cnbc.com/2026/06/24/morgan-stanley-china-humanoid-robot-market-forecast.html) / [TechRadar](https://www.techradar.com/ai-platforms-assistants/the-future-has-arrived-chinas-power-grid-will-soon-be-run-by-an-army-of-humanoid-robots-and-robot-dogs-as-state-announces-usd1-billion-investment-in-8-500-robo-helpers)

- **Humanoid leaders:** Unitree (10,000–20,000 unit 2026 target; STAR Market IPO cleared June 1) and Agibot (10,000th cumulative unit in Q1 2026) together projected to hold ~80% of China's 2026 humanoid market. [TechTimes](https://www.techtimes.com/articles/317632/20260602/unitree-ipo-cleared-agibot-hits-10000-units-china-humanoid-robot-duopoly-takes-shape.htm) (date via search index)

- **Compute & supply chain:** US BIS confirmed June 1 that AI chip restrictions extend to Chinese-headquartered firms operating outside China. [Al Jazeera](https://www.aljazeera.com/economy/2026/6/1/us-says-ban-on-ai-chip-shipments-applies-to-chinese-firms-outside-china) Domestic alternatives (Horizon Robotics, Black Sesame, Cambricon) are the primary beneficiaries; China's humanoid supply chain ramp is structurally decoupled from US silicon.

- **Policy:** MIIT + SASAC mandating local government and SOE integration of embodied AI in manufacturing, logistics, retail, and healthcare — 10,000 commercial units target by year-end 2026. [eWeek](https://www.eweek.com/news/humanoid-robots-work-mode-2026-apac-china/)

---

## 7. Policy / standards / safety

- **EU AI Act Omnibus (May 7, background):** Deferred main high-risk compliance deadline. Annex III systems: Dec 2, 2027. Annex I systems in regulated products (covers many industrial robots): Aug 2, 2028. Reduces near-term compliance pressure for robotics OEMs. [SureCloud](https://www.surecloud.com/resource-hub/eu-ai-act-complete-compliance-guide) (date via search index)

- **ISO 10218 revision:** CEN/TC 310 and ISO jointly revising prEN ISO 10218-1/-2 (industrial robot safety requirements) in coordination with EU AI Act standardization. No specific update today. [EU Interoperable Europe Portal](https://interoperable-europe.ec.europa.eu/collection/rolling-plan-ict-standardisation/robotics-and-autonomous-systems-rp-2026) (date via search index)

- **US export controls:** No new robotics-specific action in the last 24h. Background: BIS June 1 guidance extended AI chip restrictions to Chinese entities operating outside China.

---

## 8. Conferences & signals

**Automate 2026 — McCormick Place, Chicago (June 22–25, wraps today)**
- Largest edition in the show's 50-year history: 50,000+ attendees, 1,000+ exhibitors, 450,000 sq ft.
- **NVIDIA-sponsored Humanoid Robot Pavilion** on the floor; 20+ humanoid organizations demonstrating.
- **Humanoid Robot Forum** ran June 23–24.
- Headline silicon/platform announcement: **NVIDIA Halos for Robotics** (June 22) ← covered in §5.
- Headline product launches: **Kawasaki RL030N 8-DOF** (§2), **ABB Physical AI Toolchain + PoWa cobot** (§2).
- Headline funding event: **Agility Robotics $2.5B SPAC** (June 24, §1) — dropped at the show's penultimate day.
- [Automate Show](https://www.automateshow.com/education-networking/humanoid-robot-pavilion) / [TechTimes preview](https://www.techtimes.com/articles/318805/20260621/automate-2026-opens-monday-nvidia-pavilion-marks-humanoid-robot-shift-production.htm)

**ICRA 2026** — Vienna, June 1–5 (concluded). No carry-over announcements today.

---

## So what — strategic implications

1. **Agility SPAC sets the humanoid-IPO template.** $2.5B at 9 sites and 65K hours of operation — this is the pricing baseline the market now has for a humanoid OEM at early commercial scale. Watch Figure, 1X, and Apptronik for follow-on filings. Foxconn's PIPE leadership signals Asian manufacturing as the default scale-up partner.

2. **NVIDIA is winning the safety layer, not just the compute layer.** Halos for Robotics is a certification-lock play. Once Agility certifies Digit v5 against Halos, the cost of switching away from IGX Thor is not just silicon — it's re-certification from scratch. **Intel has no equivalent certified-safety answer for humanoids.** This is the most strategically important gap to close.

3. **China's 50K unit target is now analyst consensus, not aspiration.** Morgan Stanley's second upward revision in 6 months, anchored by a $1B State Grid order, signals that commercial validation has crossed the threshold. The Robotera + SF Express/China Post deployments show logistics as the first mass-volume vertical. US chip restrictions are accelerating Horizon/Black Sesame adoption in the supply chain — Intel and NVIDIA are being structurally excluded from the world's largest humanoid ramp.

4. **Automate 2026 marks the pivot from "can robots do this?" to "how fast can we deploy at scale?"** The show's dominant discourse was deployment contracts, not demo capabilities. Physical AI toolchains (ABB), safety certification (NVIDIA Halos), and 8-DOF dexterity (Kawasaki) are the three technology gaps the industry is closing this year for production readiness.
