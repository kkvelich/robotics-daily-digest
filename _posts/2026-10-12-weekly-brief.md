---
layout: post
title: "Weekly Robotics Brief — 2026-10-12"
date: 2026-10-12
tags: [funding, products, humanoids, foundation-models, deployments, silicon, china, conferences]
---

# Weekly Robotics Brief — Week of 2026-10-12

## TL;DR

- **Boston Dynamics** appoints Rohit Prasad (ex-Amazon Alexa AGI head) as CEO — Amazon AI pedigree arrives at the most recognized robotics brand.
- **Figure AI** decommissions its entire F.02 fleet by melting them down, accelerating to F.03 and previewing F.04 — the fastest hardware iteration cycle in humanoid history.
- **RobCo** hits $1B+ unicorn valuation on a $40M secondary led by Sequoia/Lightspeed; CEO relocates to US ahead of "Alfie" two-arm robot launch in March 2027.
- **IROS 2026** (Pittsburgh, Sep 27–Oct 1) concluded with 7,000+ attendees and 170+ exhibitors; post-event coverage through this week shows China's EngineAI and Agility Robotics as standouts on the floor.
- **AgiBot** overtook Unitree as the #1 global humanoid vendor by unit volume in H1 2026 (~5,900 units, 31% market share) — Chinese companies now account for >97% of humanoid shipments.

---

## 1. Funding & M&A

| Company | Stage | Amount | Lead | What they build | Compute | Source |
|---|---|---|---|---|---|---|
| RobCo (Germany) | Secondary | $40M | Sequoia, Lightspeed | Self-learning industrial robot arms; "Alfie" two-arm model launching Mar 2027 | Undisclosed | [SiliconCanals](https://siliconcanals.com/robco-raises-39-1m/) (date via search index, Oct 5 2026) |
| Teradyne → Bright Machines | Investment | Undisclosed | Teradyne (UR parent) | Software-defined manufacturing cells | Undisclosed | [The Robot Report](https://www.therobotreport.com/robotics-news/) (Oct 5 2026) |

**Notes:**
- RobCo deal structure: mostly secondary share sales by employees; doubles valuation to $1B+ vs. January Series C. CEO Roman Hoelzl relocating to US.
- Teradyne/Bright Machines: strategic rather than financial — UR parent deepening software-defined manufacturing play.
- Field.ai $60M (AI robot control software, $10B valuation) closed ~Oct 2 — just outside the 7-day window; watch for customer announcements.

---

## 2. Product Launches & Demos

**Boston Dynamics — new humanoid hand design (Oct 5)**
- Announced improved dexterous hand for its Atlas humanoid. No silicon details released.
- Source: [The Robot Report](https://www.therobotreport.com/robotics-news/) (Oct 5, 2026)

**Figure AI — F.02 fleet decommissioning (Oct 6)**
- Retired F.02 fleet sent to 75-tonne electric arc furnace to be melted. F.03 is current production platform, F.04 in development. BMW Spartanburg deployment running on F.03.
- Source: [EE News Europe](https://www.eenewseurope.com/en/figure-melts-f02-humanoid-robot-fleet/) (date via search index, Oct 6, 2026)

**TwelveLabs — Pegasus 1.6 video model for robotics (Oct 6)**
- First-person video understanding model targeting robotics developers. Allows robots to index and query continuous video streams. Silicon-agnostic.
- Source: [The Robot Report](https://www.therobotreport.com/robotics-news/) (Oct 6, 2026)

**Overview AI — OV Spark inspection cameras (Oct 6)**
- New edge-compute inspection cameras available through Overview AI and distribution partners.
- Source: [The Robot Report](https://www.therobotreport.com/robotics-news/) (Oct 6, 2026)

**RobCo — "Alfie" two-arm self-learning robot (announced this week, launch Mar 2027)**
- Dual-arm, self-learning configuration for industrial tasks. March 2027 commercial release.
- Source: [The Outpost](https://theoutpost.ai/news-story/robco-doubles-valuation-to-1b-as-physical-ai-robotics-gains-momentum-in-manufacturing-31729/) (Oct 5, 2026)

---

## 3. Foundation Models & Software

**NVIDIA Isaac GR00T N1.7 — General Availability**
- N1.7 (3B params, Cosmos-Reason2-2B/Qwen3-VL backbone) now GA on [GitHub](https://github.com/NVIDIA/Isaac-GR00T), Apache 2.0 code / NVIDIA Open Model Agreement for weights. Early access launched April 17, 2026; GA confirmed this week.
- Adopters include AgiBot, LG Electronics, NEURA Robotics, Noble Machines.
- ⚠️ **N2 (world action model architecture) previewed at GTC March 2026; GA targeted end-2026.**
- Source: [NVIDIA Research](https://research.nvidia.com/labs/gear/gr00t-n1_6/) / [GitHub](https://github.com/NVIDIA/Isaac-GR00T)

**ROS 2 "Lyrical" — post-ROSCon coverage**
- ROSCon 2026 (Toronto, Sep 22-24) featured a keynote on "Accelerated Memory Transports in ROS 2 Lyrical" — new release name confirmed. NVIDIA announced a major release at the event; formal release notes not yet published as of this week.
- Source: [NVIDIA Developer Forums](https://forums.developer.nvidia.com/t/community-guide-to-roscon-2026-toronto/383670)

**MIT Technology Review — skeptic take (Oct 8)**
- Argues that despite AI breakthroughs, practical commercial robot deployment is not imminent. Useful counter-signal for deployment forecasts.
- Source: [MIT Technology Review](https://technologyreview.com/2026/10/08/1145923/ai-breakthroughs-in-robotics-wont-change-your-life-any-time-soon) (Oct 8, 2026)

---

## 4. Customer Deployments

**Figure F.03 at BMW Spartanburg**
- Figure has returned F.03 to the Spartanburg plant following the F.02 decommission. Pilot-to-expanded-deployment trajectory confirmed; specific task counts/volumes not disclosed this week.
- Source: [EE News Europe](https://www.eenewseurope.com/en/figure-melts-f02-humanoid-robot-fleet/) (Oct 6, 2026)

**Agility Robotics Digit — 9 customer sites**
- From September 2026 recap (just outside 7-day window): Agility confirmed Digit deployed at 9 customer sites as it pursues a SPAC merger to go public.
- Source: [The Robot Report](https://www.therobotreport.com/top-10-robotics-stories-of-september-2026/) (Oct 5 recap, date via search index)

**Jabil + Apptronik — Apollo in active manufacturing**
- Jabil is working with Apptronik to bring the Apollo humanoid into active manufacturing environments. No production volumes disclosed.
- Source: [The Robot Report](https://www.therobotreport.com/jabil-discusses-pace-humanoid-robot-development-production/) (Oct 8, 2026)

---

## 5. Competitive Silicon Watch

⚠️ **No new October 2026 chip announcements confirmed this week.** Current competitive landscape:

| Chip | Vendor | Peak TOPS | Power | Robotics status |
|---|---|---|---|---|
| Jetson AGX Thor | NVIDIA | 2,070 (FP4) | 40–130W | Default for humanoid/AMR; Thor T3000/T2000 smaller modules added Jul 2026 |
| Hailo-10H | Hailo | 40 TOPS (INT4) / 20 TOPS (INT8) | 2.5W | Direct DDR interface enables LLM/VLM on-chip; strong SWaP-C case |
| Dragonwing QCS8550 | Qualcomm | Up to 700 TOPS (platform) | — | 5G-native; strong in connected AMR/drone; no major robotics design win announced |
| Core Ultra Series 3 | Intel | 180 TOPS (platform) | — | DFI Embedded World 2026 reference platform; Computex "Ella" coffee robot demo |
| CV7 | Ambarella | — | — | CES Jan 2026; perception/vision focus; no new Oct announcement |

**⚠️ Intel pressure assessment:** NVIDIA's GR00T N1.7 GA cements Isaac as the de-facto robot AI software stack, pulling system integrators toward Jetson Thor. Intel's OpenVINO robotics narrative needs a high-profile design win or a GR00T/Isaac compatibility story to stay relevant. The 180-TOPS Core Ultra Series 3 platform remains the best Intel bet for cost-sensitive deployments, but the software ecosystem gap is widening.

---

## 6. China Robotics Ecosystem

**Humanoids — AgiBot surpasses Unitree**
- AgiBot shipped ~5,900 units in H1 2026 (31% global share), overtaking Unitree as the world's #1 humanoid vendor by volume (Bloomberg/SCMP; date: Aug 12, 2026 — context for current competitive picture).
- Chinese vendors account for >97% of global humanoid shipments.
- Source: [DigiTimes](https://www.digitimes.com/news/a20260812PD207/shipments-robot-2026-market-data.html) / [SCMP](https://www.scmp.com/tech/tech-trends/article/3363544/agibot-overtakes-unitree-top-global-humanoid-robot-vendor-first-half-amid-ipo-push) (date via search index)

**XPeng IRON — automated production line (Sep 8 context)**
- XPeng launched an automated humanoid production line Sep 8, 2026; targeting mass production by end-2026, external deliveries 2027. $900M raised at $6.3B post-money.
- Source: [ExplainX](https://explainx.ai/blog/xpeng-iron-humanoid-robot-factory-2026) / [iFactoryApp](https://ifactoryapp.com/industries/manufacturing-plant/chinese-humanoid-manufacturing-agibot-xpeng-ubtech-byd)

**Unitree — post-IPO**
- Listed on STAR Market (688836) August 19, 2026 at 460-629% first-day pop. CEO forecasting 10,000–20,000 unit deliveries in 2026 (company projection). No new Oct announcements surfaced.
- Source: [Bloomberg](https://www.bloomberg.com/news/articles/2026-08-18/unitree-robotics-set-to-debut-after-904-million-shanghai-ipo) / [CNBC](https://www.cnbc.com/2026/08/06/chinese-humanoid-robot-maker-unitree-prices-ipo-at-9-billion-valuation.html)

**Government policy (Jun 2026 context — no new Oct announcements found)**
- MIIT/SASAC June 8, 2026 action plan: 100+ high-value scenarios, 10,000-unit deployment capability by year-end, usage-based leasing models. National standard system lifecycle coverage published Mar 2026.
- Source: [Embodied Global](https://embodiedglobal.com/en/article/china-miit-sasac-humanoid-robot-real-scenario-training-action-2026)

**D-Robotics at ROSCon**
- D-Robotics (Horizon Robotics subsidiary) exhibited at ROSCon Toronto Sep 22-24.
- Source: [Open Robotics Discourse](https://discourse.openrobotics.org/t/d-robotics-at-roscon-global-2026-let-s-connect-in-toronto/58247)

---

## 7. Policy / Standards / Safety

**FCC import restriction on mobile robots (Jul 2026 — active context)**
- FCC will no longer grant equipment authorizations for new models of humanoid robots, robot dogs, and AMRs unless manufactured on US soil. EU industry body VDMA filed opposition in August 2026.
- Source: [VDMA Position Paper](https://www.vdma.eu/documents/d/group-34568/2026-08-vdma-position-fcc-covered-list-decision)

**EU AI Act — high-risk deadlines shifted**
- Digital Omnibus settlement pushed high-risk AI system deadlines to Dec 2027 / Aug 2028 (from Aug 2026). Medical device robots remain in-scope as high-risk.
- Source: [Bird & Bird](https://www.twobirds.com/en/insights/2026/smart-robots,-dual-regulations-navigating-the-ai-act-and-machinery-compliance) / [Freshfields](https://www.freshfields.com/en/our-thinking/blogs/technology-quotient/embodied-ai-decoded-1-a-global-snapshot-of-the-rules-reshaping-robotics-and-emb-102n888)

*Nothing material on ISO 10218, FDA clearances, or OSHA actions this week.*

---

## 8. Conferences & Signals

**IROS 2026 — wrap-up (Sep 27–Oct 1, Pittsburgh)**
- 7,000+ attendees, 170+ exhibitors. Post-conference coverage running through this week.
- Standout floor demos: Agility Robotics Digit (logistics), EngineAI humanoid boxing demo (China).
- Keynotes covered: surgery robotics, embodied AI, soft robotics, Sony AI "Ace" table tennis robot.
- CMU hosted facility tours Oct 1. Workshop: "Toward Human-Level Robotic Teammates" (Oct 1).
- Sources: [IROS 2026 official](https://2026.ieee-iros.org/) / [CMU News](https://www.cmu.edu/news/stories/archives/2026/october/cmu-robotics-expertise-and-facilities-attract-iros-2026-conference-attendees) / [Hoodline](https://hoodline.com/2026/09/pittsburgh-s-iros-gathering-connects-robotics-research-with-questions-of-real-world-use/)

**ROSCon 2026 — Toronto, Sep 22–24 (post-event)**
- ~1,000 attendees. NVIDIA's major announcement centered on ROS 2 "Lyrical" (accelerated memory transports). PAL Robotics presented ros2_control + MuJoCo simulation integration. eSOL/selfpatch.ai: production diagnostics for ROS 2.
- Source: [NVIDIA Dev Forums](https://forums.developer.nvidia.com/t/community-guide-to-roscon-2026-toronto/383670) / [Robotics Seabass](https://roboticseabass.com/2026/09/28/conference-season-2026-roscon-and-iros/)

**⚡ RoboBusiness 2026 — coming Oct 20–21, Santa Clara**
- Keynote panel: "Beyond the Demo: AI in Production Robots." Watch for deployment volume disclosures and commercial milestone announcements.
- Source: [The Robot Report](https://www.therobotreport.com/registration-is-open-for-robobusiness-2026/)

---

## So What — Strategic Implications

1. **Boston Dynamics CEO hire signals Amazon ecosystem play.** Rohit Prasad built Alexa and Amazon's AGI org. Boston Dynamics under Hyundai now has a leader who knows how to bridge consumer AI with hardware deployment at scale. Watch for Atlas entering Amazon warehouse pilots or Alexa integration in service robots.

2. **Figure's F.02 melt signals 18-month hardware cadence.** Burning an entire fleet to move to F.03 — with F.04 already in development — means Figure is iterating faster than any auto OEM can plan around. Customers betting on multi-year humanoid partnerships should demand software abstraction layers, not hardware lock-in.

3. **NVIDIA GR00T N1.7 GA widens Intel's software gap.** With GR00T N1.7 openly licensed, commercially available, and backed by AgiBot/NEURA/LG adoptions, NVIDIA's Isaac platform is now the default robot AI stack. Intel's OpenVINO has no equivalent robot policy model. Intel must either partner with or enable GR00T to remain relevant in edge-robotics compute decisions.

4. **China's >97% humanoid market share is a supply-chain fact, not a forecast.** AgiBot topping Unitree with 5,900 units in H1 is a real volume milestone. Western OEMs sourcing actuators, sensors, or sub-assemblies from Chinese humanoid supply chains face accelerating FCC/BIS scrutiny — the July 2026 FCC import rule makes this existential for product planners.

5. **RoboBusiness (Oct 20–21) is the near-term signal watch.** "Beyond the Demo" keynote framing means vendors will either show real deployment numbers or be exposed. Agility's 9-site Digit deployment and Apptronik/Jabil's manufacturing work are the most credible stories to test.

---
*Tags: funding, products, humanoids, foundation-models, deployments, silicon, china, conferences*
