---
layout: post
title: "Weekly Robotics Brief — 2026-09-28"
date: 2026-09-28
tags: [funding, silicon, humanoids, foundation-models, deployments, china, conferences]
---

# Weekly Robotics Brief — Week of 2026-09-28

## TL;DR

- **Microchip Technology closes Hailo acquisition (Sept 21):** edge-AI accelerator consolidation continues; Hailo-8/10 gains Microchip’s supply chain, distribution, and No-EOL guarantee — strengthening the non-Intel, non-NVIDIA edge compute stack.
- **NVIDIA releases Isaac ROS 5.0 at ROSCon Toronto (Sept 22):** agentic AI coding workflows and ROS 2 Lyrical support deepen the Isaac ecosystem lock-in for robot developers.
- **Qualcomm acquires PickNik Robotics (Sept 27, announced at IROS kickoff):** folding MoveIt into Dragonwing stack is a full silicon-to-software vertical play — direct challenge to Intel’s OpenVINO Physical AI story.
- **EdgeCortix unveils RAIDEN chiplet (Sept 24):** 3.36 PFLOPS FP4, claims ~1.6× Jetson AGX Thor; Kawasaki Heavy Industries design win for aerospace/defense — a credible new entrant at thick-edge compute.
- **IROS 2026 underway in Pittsburgh (Sept 27–Oct 1)** and ROSCon 2026 wrapped in Toronto — the two premier events delivered the week’s highest-signal announcements.

---

## 1. Funding & M&A

| Company | Stage | Amount | Lead | What they build | Compute | Source |
|---|---|---|---|---|---|---|
| ViaBot | Series A | $24M | Stalwart Ventures, Walden Intl, Era Ventures | Autonomous outdoor service robots (trash/debris/security) | Undisclosed | [Parsers Weekly, Sep 22](https://parsers.substack.com/p/funding-rounds-report-weekly-of-september-6c0) (date via search index) |
| Planted Solar | Series A+ | $31.8M | Google, Khosla Ventures, Breakthrough Energy, Gigascale Capital | Autonomous solar + field robotics for power deployment | Undisclosed | [Parsers Weekly, Sep 22](https://parsers.substack.com/p/funding-rounds-report-weekly-of-september-6c0) (date via search index) |
| O-ID | Pre-seed | $1.2M | Undisclosed | Modular humanoid robots for Japanese manufacturing | Undisclosed | [The AI Insider, Sep 25](https://theaiinsider.tech/2026/09/25/japans-o-id-raises-1-2m-in-pre-seed-funding-to-develop-modular-humanoid-robots-for-factories/) |
| **PickNik Robotics** | **Acquisition (announced)** | **Undisclosed** | **Qualcomm** | MoveIt / open-source manipulation stack | Dragonwing | [Qualcomm PR, Sep 27](https://www.qualcomm.com/news/releases/2026/09/qualcomm-to-acquire-picknik-to-advance-the-future-of-open-roboti) |
| **Hailo** | **Acquisition (closed)** | **Undisclosed** | **Microchip Technology** | Edge AI accelerators, vision & robotics processors | Hailo-8/10 | [GlobeNewswire, Sep 21](https://www.globenewswire.com/news-release/2026/09/21/3365532/0/en/microchip-technology-completes-acquisition-of-hailo.html) |

Two acquisitions in the same week mark an inflection in edge-AI consolidation. Standalone edge-AI accelerator independents are disappearing into larger chipmakers.

---

## 2. Product launches & demos

**Qualcomm Dragonwing IQ10 — General Availability (September 2026)**
700 TOPS, 18 Oryon CPU cores, 64 GB LPDDR5x ECC memory. Announced at CES in January; 10 early-access partners (including NEURA Robotics and Thundercomm) from June; now GA. Handles up to 12× GMSL2 cameras, LiDAR, ToF, and IMU. Targets humanoid and industrial-robot “brain” use cases with full ROS 2 integration and cloud fleet management via Qualcomm AI Hub. Direct Jetson AGX Thor challenger. [[NAND Research](https://nand-research.com/qualcomms-dragonwing-iq10-robotics-reference-design/)] [[Qualcomm](https://www.qualcomm.com/news/releases/2026/01/qualcomm-introduces-a-full-suite-of-robotics-technologies-power)]

**EdgeCortix RAIDEN chiplet — Unveiled Sept 24** ⚠️ Intel pressure
Scalable chiplet architecture for “thick-edge” physical AI: single-die X1 through four-die X4 flagship. X4 specs: 3.36 PFLOPS FP4, 256 GB memory, 548 GB/s memory bandwidth, 1.54 TB/s die-to-die bandwidth. Kawasaki Heavy Industries selected RAIDEN for next-generation AI aerospace/defense products; Unigen developing RAIDEN-based edge-server platforms. Customer sampling Q1 2027; volume production H2 2027. [[HPCwire, Sep 24](https://www.hpcwire.com/off-the-wire/edgecortix-unveils-raiden-a-scalable-energy-efficient-ai-chiplet-platform-for-physical-ai/)] [[Embedded, Sep 24](https://www.embedded.com/edgecortix-launches-scalable-raiden-ai-chiplet-platform)]

**Epson AX6 Collaborative Robot**
Epson unveiled the AX6 cobot this week. Additional specifications and deployment details emerging from the IROS 2026 floor. [[Robot & AI Daily Digest, Sep 26](https://note.com/like_oxalis4338/n/n6dc1a815550b)] (date via search index)

---

## 3. Foundation models & software

**NVIDIA Isaac ROS 5.0 — Released Sept 21/22 at ROSCon Toronto**
Four headline additions:
1. **Agentic AI workflows** — AI coding agents can build, tune, and deploy robot applications alongside human engineers.
2. **ROS 2 Lyrical Luth + Ubuntu 24.04 support** — moves the stack to the latest LTS ecosystem.
3. **Breaking change**: NITROS accelerated-messaging APIs replaced by standard `rosidl::Buffer`; teams using NITROS directly must rewrite.
4. **Isaac Skills** — reusable packages including FoundationStereo (stereo perception fine-tuning) and FoundationPose (object tracking), available free and open-source.

[[Unite.AI, Sep 23](https://www.unite.ai/nvidias-isaac-ros-5-0-adds-agentic-skills-and-ros-lyrical-support/)] [[The AI Insider, Sep 23](https://theaiinsider.tech/2026/09/23/nvidia-releases-isaac-ros-5-0-with-new-ai-agent-tools-for-robotics-developers/)]

**Intrinsic AI Challenge — Winners Announced Sept 23 at ROSCon**
Intrinsic CEO Wendy Tan White announced the top five global winners of the AI for Industry Challenge, a competition to solve dexterous cable routing and assembly for server manufacturing. [[Intrinsic / ROSCon 2026](https://www.intrinsic.ai/events/roscon-2026)]

---

## 4. Customer deployments

**AGIBOT crosses ~20,000 cumulative units shipped** (Sept ~25–26)
China’s top global humanoid shipper by volume (43%+ of H1 2026 global market per Counterpoint Research) reached this milestone this week. The company shipped ~9,700 units in H1 2026 alone and is targeting US$142M revenue for the full year. An IPO in Hong Kong is under consideration. [[Yahoo Finance](https://finance.yahoo.com/news/chinas-agibot-targets-us-142-093000135.html)] [[Robotics & Automation News, Sep 18](https://roboticsandautomationnews.com/2026/09/18/agibot-claims-top-spot-in-global-humanoid-robot-shipments-in-first-half-of-2026/104930/)] (date via search index for 20,000 milestone)

**IFR: 5 million operational industrial robots worldwide**
The International Federation of Robotics reported this week that the global stock of operational industrial robots crossed 5 million units — a symbolic milestone confirming the scale of the automation wave underway. [[Robot & AI Daily Digest, Sep 26](https://note.com/like_oxalis4338/n/n6dc1a815550b)] (date via search index)

---

## 5. Competitive silicon watch ⚠️

| Vendor | Event this week | Intel pressure assessment |
|---|---|---|
| **Microchip/Hailo** | Acquisition closes Sept 21; 100+ customers, 10,000 developers added; No-EOL pledge on Hailo-8/10 | ⚠️ Hailo now has Microchip’s industrial distribution, supply chain stability, and longevity guarantees — advantages Intel NPU modules lack in the OEM channel |
| **Qualcomm** | Dragonwing IQ10 now GA (700 TOPS, 64 GB ECC); PickNik/MoveIt acquisition announced Sept 27 | ⚠️ Full-stack silicon + OS + manipulation planning path; software moat Intel currently lacks for robotics |
| **EdgeCortix** | RAIDEN chiplet unveiled Sept 24; X4: 3.36 PFLOPS FP4, ~1.6× Jetson AGX Thor claim; Kawasaki design win | ⚠️ Credible new challenger for high-performance thick-edge robotics compute; aerospace/defense channel entry |
| **NVIDIA** | Isaac ROS 5.0 ecosystem deepening | Neutral — ecosystem play, not direct silicon competition with Intel this week |

**Bottom line:** Intel faced meaningful pressure from three directions simultaneously this week with no offsetting announcement. The Qualcomm software acquisition is the most strategically significant — it closes the gap between silicon and developer workflow that Intel’s OpenVINO Physical AI currently occupies.

---

## 6. China robotics ecosystem

**AGIBOT — ~20,000 cumulative units; considering HK IPO**
Confirmed top global humanoid shipper in H1 2026, with AgiBot and Unitree together projected to hold ~80% of China’s market. Co-founder Yao Maoqing has called humanoid robots 13 weeks from China’s MIIT/SASAC year-end deployment mandate. [[Yahoo Finance](https://finance.yahoo.com/news/chinas-agibot-targets-us-142-093000135.html)]

**Mifeng — Crowdsourcing Platform for Physical Training Data**
Mifeng launched a crowdsourcing platform to collect embodied AI training data from real-world environments this week, targeting the physical-world data bottleneck for robot policy learning. [[Robot & AI Daily Digest, Sep 26](https://note.com/like_oxalis4338/n/n6dc1a815550b)] (date via search index)

**Chatham House: “Is China’s humanoid robot industry a bubble?”**
Chatham House published a risk assessment this month questioning whether China’s humanoid ramp will generate real economic returns or result in stranded state-subsidized capacity. The backdrop: MIIT/SASAC mandates 10,000 deployed humanoid units and 100+ high-value applications across Chinese industry by Dec 31, 2026; Shanghai subsidizes up to 30% of project costs. [[Chatham House, Sep 2026](https://www.chathamhouse.org/2026/09/chinas-humanoid-robot-industry-bubble)]

**Context — policy:** MIIT’s Humanoid Robot and Embodied Intelligence Standardization Committee released the first national standard system in March 2026 covering the full humanoid lifecycle. The Dec 2026 deployment mandate deadline is now 13 weeks away. [[China Briefing](https://www.china-briefing.com/news/chinese-humanoid-robot-market-opportunities/)]

---

## 7. Policy / standards / safety

*Nothing material this week.*

---

## 8. Conferences & signals

**ROSCon 2026 — Toronto, Sept 22–24 (just wrapped)**
The week’s highest-signal software event for the ROS ecosystem. Key outputs: NVIDIA Isaac ROS 5.0 launch; Intrinsic AI Challenge winners announced; D-Robotics exhibited; Canonical/Ubuntu presence. 15th annual ROS developer conference. [[ROSCon 2026 / MassRobotics](https://www.massrobotics.org/event/roscon-2026/)] [[NVIDIA at ROSCon](https://www.nvidia.com/en-us/events/roscon/)]

**IROS 2026 — Pittsburgh, Sept 27–Oct 1 (ongoing now)**
4,000+ researchers, ~2,000 papers, David L. Lawrence Convention Center. Week’s keynotes: Elena De Momi (autonomous surgery open questions), Naomi Fitter (socially-informed robot context awareness), Greg Chirikjian (affordance learning from hyper-redundancy), and **Genta Suzuki / Fujitsu** (“Kozuchi Physical OS: A Research Strategy for Scalable Physical AI”) — a Tier-1 industrial tech company articulating a physical AI platform strategy. Special panels on robotics startups, space robotics, and generalist vs. specialist robots. [[IROS 2026](https://2026.ieee-iros.org/)] [[CMU news, Sep 2026](https://www.cmu.edu/news/stories/archives/2026/september/global-conference-in-pittsburgh-puts-carnegie-mellons-robotics-leadership-in-the-spotlight)]

---

## So what — strategic implications

1. **Qualcomm is executing a full vertical stack and doing it at IROS.** Announcing the PickNik/MoveIt acquisition on the day IROS opens in Pittsburgh — in front of 4,000 robotics researchers — is deliberate positioning. Qualcomm now owns the path from silicon (Dragonwing IQ10) through OS/runtime to manipulation planning (MoveIt). This directly competes with Intel’s OpenVINO Physical AI integration story, but with meaningfully higher-performance silicon underneath it.

2. **Hailo inside Microchip is the biggest long-term supply-chain shift.** Hailo-8/10 accelerators are already designed into dozens of AMR and industrial vision products. Microchip’s industrial distribution, No-EOL commitment, and embedded-systems OEM relationships give those design wins durability. Watch for Hailo compute to displace general-purpose SoCs in next-generation cobot vision systems over the next 12–18 months.

3. **Isaac ROS 5.0’s agentic pivot is a developer moat play.** Integrating AI coding agents that build and tune robot apps raises the switching cost of the Isaac ecosystem before open alternatives (MoveIt + Qualcomm, LeRobot) reach feature parity. The NITROS break in this release is also a signal: NVIDIA is willing to force migration to deepen architectural alignment.

4. **China’s Dec 2026 mandate is the near-term forcing function.** With MIIT/SASAC’s 10,000-unit deployment deadline 13 weeks out and AGIBOT crossing 20,000 cumulative units, the question is whether deployed units equal productive units. Chatham House’s bubble framing will intensify through Q4 as factories report on actual task completion rates.

5. **Watch next week:** IROS 2026 runs through Oct 1 — expect research paper releases on VLA generalization benchmarks, surgical autonomy, and dexterous manipulation that will shape 2027 product roadmaps. Qualcomm’s PickNik deal will likely prompt a competitive response — watch for Intel, Open Robotics, or a ROS 2 integrator to announce a software commitment.

---

*Tags: funding, silicon, humanoids, foundation-models, deployments, china, conferences*
