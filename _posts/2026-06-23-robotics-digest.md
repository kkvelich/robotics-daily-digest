---
layout: post
title: "Robotics Brief — 2026-06-23"
date: 2026-06-23
tags: [products, silicon, humanoids, deployments, china, conferences]
---

# Robotics Market Sensing — 2026-06-23

## TL;DR
- **NVIDIA Halos for Robotics** (June 22) is the day's defining announcement — first ANAB-accredited full-stack physical AI safety system, running exclusively on IGX Thor. No Intel analog exists; this creates a certification moat across the certified-humanoid market.
- **Automate 2026** (Chicago, June 22–25) Day 1/2 produces a wave of launches: Kawasaki RL030N 8-DOF arm, ABB PoWa cobot family, Robot.com R-noid wheeled humanoid, and Novarc NovAI Autonomy welding AI — all under the banner of "physical AI."
- **Agility Digit at Toyota Canada** (7 units, RAV4 plant, RaaS) and **Atlas committed to Hyundai Metaplant + DeepMind** confirm humanoids are in sustained commercial deployment, not pilots.

---

## 1. Funding & M&A

*Nothing confirmed in the 24h window.*

---

## 2. Product launches & demos

| Product | Company | What | Silicon | Source |
|---|---|---|---|---|
| **Kawasaki RL030N** | Kawasaki Robotics | World premiere of first 8-DOF industrial arm for physical AI; 30 kg payload, 1,925 mm reach; open KRNX real-time API for ROS / ML frameworks and external AI orchestration | Not disclosed | [Kawasaki newsroom](https://kawasakirobotics.com/news/kawasaki-robotics-unveils-dexterous-physical-ai-robot-platform-advanced-automation-technologies-at-automate-2026/) |
| **ABB PoWa cobot family + Physical AI Toolchain** | ABB Robotics | High-speed, higher-payload cobots; Physical AI Toolchain covers data→training→deploy loop; ~99% sim-to-real via RobotStudio HyperReality (NVIDIA Omniverse backend) | NVIDIA Omniverse (sim) | [ABB newsroom](https://new.abb.com/news/detail/135100/prsrl-abb-robotics-launches-high-speed-powa-cobot-family) |
| **R-noid** | Robot.com | Wheeled, legless upper-body humanoid for logistics / food service; dual 7-DoF arms, 4-DoF torso, 19 deployable tasks across 6 verticals; RaaS model, 8–12 week site-to-autonomous onboarding | **π0.7** (Physical Intelligence VLA) as policy backbone; FieldAI foundation model for autonomy layer | [Unite.AI](https://www.unite.ai/robot-com-enters-the-humanoid-robotics-race-with-the-launch-of-r-noid/) |
| **NovAI Autonomy** | Novarc | Real-time vision + adaptive weld-parameter control; expands NovHub enterprise welding platform to ABB and Yaskawa six-axis arms | Not disclosed | [GlobeNewswire](https://www.globenewswire.com/news-release/2026/06/22/3315324/0/en/NOVARC-LAUNCHES-NovAI-AUTONOMY-AS-PART-OF-NovAI-SUITE-AND-EXPANDS-INTEGRATION-TO-YASKAWA-AND-ABB-ROBOTS.html) |
| **InOrbit Space Intelligence** | InOrbit.AI | Live 8-vendor federated AMR orchestration demo at Automate; RobOps Copilot enables natural-language / voice robot management across brands | Vendor-agnostic middleware | [RoboticsTomorrow](https://www.roboticstomorrow.com/news/2026/06/22/inorbitai-demonstrates-the-future-of-multi-vendor-robot-orchestration-and-physical-ai-at-automate-2026/26757/) |

---

## 3. Foundation models & software

No new model release confirmed in the 24h window. Most notable: **Robot.com R-noid** ships at commercial launch with **π0.7** (Physical Intelligence's latest VLA) as its on-robot policy — the first publicly confirmed VLA-powered commercial RaaS product announced at Automate. [Unite.AI](https://www.unite.ai/robot-com-enters-the-humanoid-robotics-race-with-the-launch-of-r-noid/)

---

## 4. Customer deployments

- **Agility Digit → Toyota Motor Manufacturing Canada** — 7 Digit units running at Woodstock, Ontario (RAV4 / RAV4 Hybrid line) under commercial RaaS agreement. CTO Pras Velagapudi confirmed details at today's Humanoid Robot Forum. [Automate.org](https://www.automate.org/robotics/industry-insights/boston-dynamics-to-begin-production-on-redesigned-atlas-humanoid-in-2026)
- **Boston Dynamics Atlas → Hyundai Metaplant (GA) + Google DeepMind** — entire 2026 Atlas production run committed to two customers. Specs: 56 DoF, 110 lb lift capacity, 360° torso, autonomous battery swap. [Robotics 24/7](https://www.robotics247.com/article/automate-2026-amrs-cobots-humanoids-orchestration-platforms-software-systems-more)

---

## 5. Competitive silicon watch ⚠️

**⚠️ NVIDIA IGX Thor — direct Intel pressure:**

NVIDIA launched **Halos for Robotics** on June 22 — industry's first full-stack physical AI safety system.

- **Compute layer:** NVIDIA **IGX Thor** + Holoscan Sensor Bridge
- **Software:** Halos OS safety stack; Outside-In Safety Blueprint for external sensor fusion
- **Certification:** World's first **ANAB-accredited** AI Systems Inspection Lab for physical AI safety (certifying bodies: TÜV Rheinland, UL Solutions, TÜV SÜD, exida, SGS, CertX)
- **First adopter:** Agility Robotics incorporating Halos into its proprietary safety system
- **FORT Robotics** (June 22): demonstrated agentic Outside-In Safety application on IGX Thor + Holoscan at Automate Humanoid Pavilion June 23

[NVIDIA GlobeNewswire](https://www.globenewswire.com/news-release/2026/06/22/3315323/0/en/NVIDIA-Announces-Halos-for-Robotics-the-Industry-s-First-Full-Stack-Safety-System-for-Physical-AI.html) | [FORT PR Newswire](https://www.prnewswire.com/news-releases/fort-robotics-extends-its-trust-layer-for-physical-ai-by-adding-outside-in-safety-in-collaboration-with-nvidia-halos-for-robotics-302804999.html)

**Intel:** No announcements visible at Automate 2026 as of this sweep.

**Qualcomm / Ambarella / Hailo / Rockchip:** Nothing confirmed June 22–23.

---

## 6. China robotics ecosystem

- **Humanoids:** No specific Unitree / AgiBot / Fourier announcement confirmed June 22–23. Background: Unitree STAR Market IPO in waiting period after June 1 committee approval; AgiBot at 10k cumulative units. [TechTimes](https://www.techtimes.com/articles/317632/20260602/unitree-ipo-cleared-agibot-hits-10000-units-china-humanoid-robot-duopoly-takes-shape.htm)
- **Compute & supply chain:** **Xingyuanzhi Robot** (Beijing, incubated by BAAI) raised cumulative ¥1B (~$138M) in 10 months for its "embodied brain" software+compute platform; AgiBot is a strategic customer with ¥500M+ pipeline. *(date via search index)* [Pandaily](https://pandaily.com/xingyuanzhi-robot-embodied-ai-brain-funding-jun2026)
- **Policy (background):** MIIT + SASAC launched the 2026 Humanoid Robot Real-Scene Training Initiative (June 9): 100+ deployment scenarios, 10k-unit capacity target by year-end. This is the active policy backdrop driving factory rollout demand. [Pandaily](https://pandaily.com/miit-sasac-humanoid-robot-real-scene-training-2026-jun2026)
- **Industrial / cobot:** *Nothing confirmed June 22–23.*
- **Deployments:** *Nothing confirmed June 22–23.*

---

## 7. Policy / standards / safety

- **NVIDIA Halos ANAB accreditation** (June 22): The NVIDIA Halos AI Systems Inspection Lab is the world's first ANAB-accredited certification program for functional and AI safety for physical AI — aligning emerging humanoid safety certification with NVIDIA's silicon stack. Implication: robots seeking enterprise/regulated-environment certification will face a Halos-shaped compliance path. [GlobeNewswire](https://www.globenewswire.com/news-release/2026/06/22/3315323/0/en/NVIDIA-Announces-Halos-for-Robotics-the-Industry-s-First-Full-Stack-Safety-System-for-Physical-AI.html)
- **EU AI Act countdown:** Full applicability August 2, 2026 — now 40 days out. Robotics OEMs face ISO 42001 compliance requirements; non-compliance penalties up to €35M or 7% of global revenue. No specific regulatory action today, but the deadline is actively reshaping product roadmaps. [HI AI Design](https://www.hiai-design.com/blog-eu-ai-act-robotics-2026)

---

## 8. Conferences & signals

**Automate 2026** — McCormick Place, Chicago, June 22–25. Largest automation show in its 50-year history: 50,000+ attendees, 1,000+ exhibitors, 450,000 sq ft.

- **Day 1 (June 22):** Physical AI declared the dominant theme across the floor. NVIDIA Halos launch, Kawasaki RL030N world premiere, ABB PoWa / Physical AI Toolchain, Robot.com R-noid, Novarc NovAI Autonomy all announced. NVIDIA-sponsored Humanoid Robot Pavilion (20+ orgs) anchors the floor.
- **Day 2 (June 23, today):** **Humanoid Robot Forum** opens (noon–5 PM CDT) — speakers from Boston Dynamics, Neura Robotics, NVIDIA, Toyota Research Institute. **A3 Automate Innovation Awards** announced (10:30 AM). FORT + NVIDIA live Outside-In Safety demo in Humanoid Pavilion.
- **Silicon note for section 5:** NVIDIA's IGX Thor / Halos / Omniverse ecosystem is the dominant compute narrative at Automate 2026. Intel has no visible counter-presence on the show floor or in press releases as of this sweep.

[Automate Show](https://www.automateshow.com/) | [Humanoid Forum](https://www.automateshow.com/education-networking/humanoid-robot-forum)

---

## So what — strategic implications

1. **NVIDIA is building a safety-certification moat around IGX Thor.** Halos + ANAB accreditation means enterprise buyers deploying humanoids in regulated environments (automotive, logistics, healthcare) will increasingly require a Halos-certified stack — which runs on IGX Thor. Intel has no equivalent certified physical AI safety architecture. This is the sharpest competitive gap opened this week.

2. **"Physical AI" is the new "collaborative robotics."** ABB, Kawasaki, Robot.com, and Novarc all converged on the term unprompted at Automate. The practical implication: on-robot inference is now a product requirement rather than a research milestone. Every new industrial arm and cobot platform is adding an AI layer — and that layer needs a compute substrate. The NPU-per-arm BOM battle is live.

3. **RaaS is the humanoid go-to-market.** R-noid, Agility Digit at Toyota, and the Humanoid Forum agenda all center on RaaS economics. This shifts competitive advantage from hardware BOM toward software stack stickiness and data flywheel quality — and lifts orchestration platforms (InOrbit, Intrinsic) to critical middleware status.

4. **China's embodied-brain stack is the mirror-image race.** Xingyuanzhi's ¥1B raise for the "embodied brain" software+compute layer, Alibaba Qwen-Robot, and ByteDance Seed Robotics are all building the same VLA + simulation + deployment pipeline — optimized for domestic factory deployment under the MIIT/SASAC mandate rather than Western certifications. Watch for Horizon Robotics and Cambricon silicon being designed into these stacks, reducing dependence on NVIDIA Jetson.
