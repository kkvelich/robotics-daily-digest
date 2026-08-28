---
layout: post
title: "Robotics Brief — 2026-08-28"
date: 2026-08-28
tags: [china, humanoids, policy, foundation-models, conferences]
---

# Robotics Market Sensing — 2026-08-28

## TL;DR
- **Teradyne vs. JAKA** (Aug 27): Teradyne Robotics filed patent infringement at Europe's Unified Patent Court against JAKA's German subsidiary — its second China-cobot IP action in 2026, with potential effect across 17+ EU states.
- **World Humanoid Robot Games 2026** wrapped Aug 26 in Beijing: 2,056 robots, 666 teams, Chinese makers dominated practical tasks; Unitree debuted its "Superman" humanoid claiming 12.66 m/s sprint and 2 m jump.
- **Thin 24h news window**: major silicon stories (NVIDIA Jetson Orin Nano 2, Intel Hot Chips) are 3 days stale; next material wave likely at IROS (Sept 27, Pittsburgh).

---

## 1. Funding & M&A

*Nothing material today.* *(Motion, Brussels, raised €1.7M pre-seed Aug 27 for a Humanoids-as-a-Service platform — below $10M threshold.)*

---

## 2. Product launches & demos

- **Carbon Robotics + iMerit** — LaserWeeder in-field AI customization: iMerit partnership enables instant model tuning from 2–3 field images via iPad app; underpins Carbon ATK (Autonomous Tractor Kit for existing tractors). Silicon: not disclosed. [The Robot Report](https://www.therobotreport.com/carbon-robotics-partners-with-imerit-to-power-instant-in-field-ai-customization/) *(date via search index)*

---

## 3. Foundation models & software

- **SelfWAM** (arXiv:2608.00725) — "A Self-Grounded Unified World Action Model for Fast Robot Control." Accepted to IROS 2026. Self-grounding mechanism targets sim-to-real gap in WAM-based robot policies. Part of a dense August cluster of world-action model papers (HiMem-WAM, EWAM, OA-WAM, ImageWAM also posted Aug 2026 on cs.RO). [arXiv cs.RO/current](https://arxiv.org/list/cs.RO/current) *(date via search index)*

---

## 4. Customer deployments

*Nothing material today.*

---

## 5. Competitive silicon watch ⚠️

*Nothing confirmed within the 24h window.*

> **3-day-old context (published Aug 25):** NVIDIA announced **Jetson Orin Nano 2** — 78 TOPS, 8 GB RAM, 2× inference performance of its predecessor at 40% lower power; available H1 2027. Early adopters: Cognex, Doosan Bobcat, Matic. [NVIDIA Newsroom](https://nvidianews.nvidia.com/news/nvidia-announces-jetson-orin-nano-2-robotics-computer-to-redefine-entry-level-edge-ai)
>
> At **Hot Chips 2026** (Aug 23–25), Intel presented three agentic-AI architectures: **Diamond Rapids** (256-core Xeon, 16 chiplets on Intel 18A-P), **Crescent Island** (480 GB LPDDR5X inference GPU, 350 W PCIe), and **Wildcat Lake** = Core Series 3 (6-core, 17 TOPS NPU, Intel 18A) targeting edge appliances and robotics. Intel claims 130+ design wins for Series 3 in edge/robotics. [StorageReview](https://www.storagereview.com/news/intel-hot-chips-2026-256-core-diamond-rapids-crescent-island-with-480gb-for-inference-and-wildcat-lake-at-the-edge) [Intel Newsroom](https://newsroom.intel.com/client-computing/intel-outlines-architectures-for-agentic-ai-at-hot-chips-2026) *(dates via search index)*
>
> **⚠️ Intel pressure signal**: Wildcat Lake's 17 TOPS NPU at edge, on Intel's own 18A process, is a direct challenge to NVIDIA Jetson Orin Nano 2's entry-level position. Pricing and H1 2027 head-to-head availability will be the real test.

---

## 6. China robotics ecosystem

- **Humanoids**: **World Humanoid Robot Games 2026** (Aug 22–26, Beijing Ice Ribbon) concluded. 2,056 robots, 666 teams, 51 disciplines including track & field, football, martial arts, and practical factory scenarios. Autonomy-only rule (no teleoperation) produced procurement-grade performance data. **Tiangong Ultra** (Beijing Humanoid Robot Innovation Center) topped the large-category 100 m. **Unitree** unveiled its "Superman" platform at the event — claims 12.66 m/s sprint (vs. Bolt's 10.44 m/s peak) and 2 m vertical jump. **AgiBot** led practical scenario/factory-floor medals. Tsinghua "Huoshen" team won 5v5 football final. [RobotTesters](https://robottesters.com/article-world-humanoid-robot-games-2026) *(date via search index)*, [RoboPodium](https://robopodium.com/whrg-2026) *(date via search index)*

- **Industrial / cobot**: **Teradyne Robotics vs. JAKA** — Patent infringement case filed Aug 27 at Unified Patent Court (UPC), Copenhagen, against JAKA GmbH (German subsidiary). Allegations cover both hardware and software patents on UR cobot systems. Ruling would cover 17+ UPC member states plus UK and Spain. Teradyne's second China-cobot IP action in Europe in 2026; first was against Elite Robots in February 2026 (copyright). [Robotics & Automation News](https://roboticsandautomationnews.com/2026/08/27/teradyne-robotics-launches-patent-infringement-case-against-chinese-competitor-at-european-patent-court/104503/) [RoboticsTomorrow](https://www.roboticstomorrow.com/news/2026/08/27/collaborative-robot-market-leader-teradyne-robotics-starts-patent-infringement-case-against-chinese-robot-competitor-at-european-patent-court/27010/)

- **Compute & supply chain**: *Nothing material today.*

- **Policy**: Teradyne vs. JAKA escalation pattern signals that Western cobot IP holders are using European courts as a strategic lever as Chinese makers gain EU market share.

- **Deployments**: *Nothing new within 24h.* (Background: AgiBot shipped ~8,400 units H1 2026, 44% global humanoid market; UBTECH Walker S2 deployed at BYD, Foxconn, FAW-VW, Geely, Airbus.)

---

## 7. Policy / standards / safety

- **Teradyne Robotics v. JAKA at European Unified Patent Court** (Aug 27): Case filed in Copenhagen. Hardware and software patents covering UR collaborative robot systems alleged. Potential effect across 17+ EU states plus UK/Spain. Pattern: this is Teradyne's second China-cobot IP case in Europe this year; Elite Robots case (February) was copyright-based, this case is patent-based. Escalating legal exposure could create EU market access uncertainty for Chinese cobot makers entering 2027. [Robotics & Automation News](https://roboticsandautomationnews.com/2026/08/27/teradyne-robotics-launches-patent-infringement-case-against-chinese-competitor-at-european-patent-court/104503/)

---

## 8. Conferences & signals

- **World Humanoid Robot Games 2nd Edition** (Aug 22–26, Beijing National Speed Skating Oval): Concluded Aug 26. Key signal: the autonomy-only format — no remote control, no assists — converts spectacle into competitive benchmarks. AgiBot winning practical tasks (not just speed records) is the procurement-relevant headline. Unitree's "Superman" reveal at the event positions it as a platform pitch ahead of its August IPO momentum. Coverage active Aug 27. [RoboZaps](https://blog.robozaps.com/b/humanoid-robot-news-week-august-17-24-2026) *(date via search index)*

- **Hot Chips 2026** (Aug 23–25, Stanford, Palo Alto — concluded just outside 24h window): Intel's Wildcat Lake edge SoC and NVIDIA's Vera Rubin architecture were the headline silicon presentations. See §5 for details. → Edge AI silicon announcements at this venue are highest-signal Intel-pressure items.

---

## So what — strategic implications

1. **Chinese cobot IP risk in Europe is becoming structural.** Teradyne now has two active EU IP cases vs. Chinese cobot makers. If UPC rules for Teradyne, JAKA faces potential EU-wide import exposure — a short-term opportunity for UR and Western cobot makers in European accounts currently evaluating Chinese alternatives.

2. **World Humanoid Robot Games as real procurement data.** The autonomy-only format makes this the first humanoid competition generating defensible performance benchmarks. AgiBot's factory-floor wins matter more to logistics/manufacturing buyers than the sprint records. Expect Tier-1 OEM vendor evaluations to reference WHRG 2026 results.

3. **Intel vs. NVIDIA edge battle enters availability race.** Both Wildcat Lake (17 TOPS NPU, Intel 18A) and Jetson Orin Nano 2 (78 TOPS) target the entry-level robotics edge segment and are slated for H1 2027 availability. Intel's performance-per-watt claims and existing OpenVINO ecosystem will be tested against NVIDIA's 3M-developer installed base. Watch design-win announcements at Embedded World 2027 as the real leading indicator.

4. **World-action model wave cresting into IROS.** Five-plus WAM papers on arXiv in August 2026 alone. IROS 2026 (Sept 27, Pittsburgh) will be dominated by world-action model results — executives should expect the VLA-vs-WAM debate to resolve into a complementary stack by year-end, not a winner-take-all outcome.
