---
layout: post
title: "Weekly Robotics Brief — 2026-10-19"
date: 2026-10-19
tags: [funding, humanoids, foundation-models, silicon, china]
---

# Weekly Robotics Brief — Week of 2026-10-19

## TL;DR

- **Physical Intelligence** opens Pi API beta (Oct 13): external devs can now fine-tune and deploy π0/π0.5 robot foundation models via hosted cloud inference — the week's biggest software unlock.
- **Five robotics startups** raised a combined ~$510M: ICON ($200M construction robots), MMI ($125M surgical), Multiply Labs ($75M pharma), Mecka AI ($60M training data), Ultra ($50M warehouse).
- **FieldAI** (NVIDIA/Gates-backed) reportedly negotiating a ~$700M raise at a $10B valuation; term sheet signed, not yet closed.
- **JAKA** debuted the Kargo50 wheeled humanoid and Zu50 (50 kg payload cobot) at CIIF 2026 Shanghai — first heavy-duty wheeled humanoid from a Chinese cobot leader.
- **RoboBusiness 2026** and **Long Horizon Physical AI Summit** both open Oct 20–21 — watch for humanoid deployment commitments and foundation-model announcements.

---

## 1. Funding & M&A

| Company | Stage | Amount | Lead | What they build | Compute | Source |
|---------|-------|--------|------|-----------------|---------|--------|
| ICON | Series D | $200M | Baillie Gifford / BlackRock | Robotic 3D-printing construction (Titan, Olympus) | Unspecified | [theaiinsider, Oct 14](https://theaiinsider.tech/2026/10/14/icon-raises-200m-in-series-d-funding-to-scale-robotic-construction-systems/) |
| MMI | Series D | $125M | BioStar Capital | Symani microsurgical robot (~3,500 surgeries at ~50 sites) | Unspecified | [automate.org](https://www.automate.org/robotics/industry-insights/robotics-raises-icon-mecka-ai-multiply-labs-mmi-ultra/) |
| Multiply Labs | Series B | $75M | NantWorks (unconfirmed) | Pharmaceutical manufacturing robots | Unspecified | [automate.org](https://www.automate.org/robotics/industry-insights/robotics-raises-icon-mecka-ai-multiply-labs-mmi-ultra/) |
| Mecka AI | Series B | $60M | Sequoia Capital | Human-motion → robot training-data platform | Cloud | [dealroom](https://dealroom.co/news/160699-mecka-raises-60m-series-b-to-turn-human-motion-into-robot-training-data/) |
| Ultra | Series A | $50M | Undisclosed | Warehouse workstation robots | Unspecified | [automate.org](https://www.automate.org/robotics/industry-insights/robotics-raises-icon-mecka-ai-multiply-labs-mmi-ultra/) |
| FieldAI | Late-stage *(rumored)* | ~$700M | TBD | AI OS for field / industrial robots | NVIDIA ecosystem | [OCBJ](https://www.ocbj.com/oc-homepage/fieldai-reportedly-raising-700m-at-10b-valuation/) |

**M&A:** No confirmed deals this week. Mobileye/Mentee Robotics (~$900M) reported earlier in H1 2026; timing unverified for this window.

**Macro context:** Global robotics/Physical AI funding is on pace for ~$48B in 2026, with capital concentrating in larger rounds (Q2 2026: $18.6B, +25% QoQ, deal count –14%). Source: [Crunchbase/FT](https://news.crunchbase.com/venture/physical-ai-funding-startups-robotics-aerospace-h1-2026/)

---

## 2. Product Launches & Demos

**JAKA Kargo50 + Zu50 — CIIF 2026, Shanghai (~Oct 13)**
- **Kargo50:** First wheeled humanoid from a major Chinese cobot maker. Handles intra-facility material movement (tote transport, engine-part delivery). Fleet coordination via JAKA EVO OS (cloud perception/planning layer; 1,000 Hz motion controller). Two units demoed coordinated engine-assembly task.
- **Zu50:** 50 kg payload cobot arm, 2.1 m reach, up to 50% faster joint speeds vs. prior gen. Targets heavy factory assembly.
- **Silicon:** Chip vendor not disclosed. EVO OS cloud stack handles perception/planning. Watch JAKA product pages for SoC details.
- Sources: [Interesting Engineering](https://interestingengineering.com/ai-robotics/china-wheeled-humanoid-robot-arm-factory-automation) (date via search index), [Pandaily](https://pandaily.com/jaka-robotics-kargo50-heavy-duty-wheeled-humanoid-zu50-cobot-ciif-2026)

**Physical Intelligence Pi API Beta — Oct 13**
- Developers upload robot data → PI manages training compute → fine-tuned model served as cloud-hosted inference on their robots.
- Models accessible: π0 and π0.5; π0.7 (steerable, April 2026) also accessible.
- Early user: Almond achieved a working deburring model for its Axol dual-arm robot after just 4 days of API iteration.
- Access via waitlist.
- Sources: [pi.website](https://www.pi.website/blog/api-beta), [unite.ai](https://www.unite.ai/physical-intelligence-opens-pi-api-beta-for-robot-foundation-models/), [theaiinsider, Oct 14](https://theaiinsider.tech/2026/10/14/physical-intelligence-opens-pi-api-beta-for-robot-model-training-and-deployment/)

---

## 3. Foundation Models & Software

**Physical Intelligence Pi API Beta (Oct 13)** — see §2. Strategic significance: moves Physical Intelligence from closed-lab research to developer ecosystem. Pattern mirrors OpenAI's GPT API expansion.

**NVIDIA Cosmos 3 Edge** *(announced July 2026; Jetson modules Q1 2027)*
- 4B-parameter world model on Nemotron, runnable on RTX / DGX / Jetson. Enables on-robot reasoning and action generation.
- Jetson Thor T2000 and T3000 ("mainstream robotics") modules targeted for Q1 2027 availability.
- 22 Japanese robotics/manufacturing leaders (FANUC, Sony, SoftBank) joining NVIDIA Cosmos Coalition.
- Sources: [aiweekly.co](https://aiweekly.co/alerts/nvidia-ships-4b-parameter-cosmos-3-edge-world-model-on-nemotron-for-jetson-thor), [newsquawk](https://newsquawk.com/headlines/nvidia-nvda-introduces-new-jetson-thor-computers-for-mainstream-robotics-and-edge-ai-expands-collaboration-with-toyota-7203-jt-on-physical-ai-in-automotive-robotics-and-urban-development-15-07-2026)

**Intel OpenVINO Physical AI** *(Computex May 2026; GA still pending H2 2026)*
- Open-source deployment framework for robot foundation models on edge fleets. Paired with Core Ultra Series 3 (Panther Lake, up to 180 total platform TOPS).
- GA not yet confirmed as shipped this week — material risk if it slips.
- Source: [neowin.net](https://www.neowin.net/news/computex-2026-intel-says-its-solved-one-of-the-biggest-physical-ai-and-robotics-issue/)

---

## 4. Customer Deployments

**Agility Robotics Digit:** 9 customer facilities; >65,000 cumulative operating hours reported in investor disclosures. Source: [wwd.com](https://wwd.com/sourcing-journal/logistics/agility-robotics-goes-public-humanoid-robots-digit-spac-merger-amazon-1239030943/)

**Amazon:** Passed 1M robots in operations network. Vulcan force-feedback arm live in Spokane, WA and Hamburg. Broader Vulcan fleet scaling expected 2027. Source: [freightwaves](https://www.freightwaves.com/news/amazon-ramps-up-delivery-speed-robotics-roll-out)

**AgiBot:** 300+ robots (including humanoids) deployed at Chimelong Spaceship Park, Hengqin, China. Source: [humanoid.guide](https://humanoid.guide/agibot-leads-h1-2026-humanoid-shipments-with-8600-units/)

*Nothing confirmed on BMW, GXO, Foxconn, or surgical/agricultural deployments this week.*

---

## 5. Competitive Silicon Watch ⚠️

**⚠️ Qualcomm Dragonwing IQ10 — GA September 2026**
- **700 TOPS AI performance**, 18 Oryon CPU cores, 64 GB LPDDR5x ECC, –40°C to +70°C, 12V/24V power input. Full Robotics Reference Design (RRD) debuted at Computex.
- Partners: Neura Robotics, Advantech, Innodisk, NEXCOM, Thundercomm, VinMotion. Kuka in discussions.
- Positioned directly against Jetson AGX Orin and Jetson Thor for industrial AMRs and humanoids.
- **Intel pressure:** Purpose-built robotics SoC at industrial temps; credible alternative to Jetson and Core Ultra for OEM design wins.
- Sources: [qualcomm.com](https://www.qualcomm.com/news/releases/2026/01/qualcomm-introduces-a-full-suite-of-robotics-technologies-power), [mysmartprice](https://www.mysmartprice.com/personal-tech/laptops-pc/laptops-pc-news/qualcomm-unveils-dragonwing-iq10-robotics-reference-design-with-up-to-700-tops-ai-performance/)

**⚠️ NVIDIA Jetson Thor T2000/T3000 — Q1 2027 availability**
- "Mainstream robotics" targeting overlaps with Intel Core Ultra Series 3 addressable market.
- Toyota collaboration on physical AI in automotive robotics adds brand weight.
- Q1 2027 slip gives Intel a narrow design-win window if OpenVINO Physical AI GA lands this quarter.
- Source: [newsquawk](https://newsquawk.com/headlines/nvidia-nvda-introduces-new-jetson-thor-computers-for-mainstream-robotics-and-edge-ai-expands-collaboration-with-toyota-7203-jt-on-physical-ai-in-automotive-robotics-and-urban-development-15-07-2026)

**Intel Core Ultra Series 3 / OpenVINO Physical AI:**
- Intel claims ~50% lower hardware cost vs. Jetson AGX Orin/Thor (marketing claim, not independently verified).
- No new Intel announcement this week. OpenVINO Physical AI GA still pending H2 2026.
- If GA slips past Q4 2026, NVIDIA and Qualcomm will have locked in key design wins before Intel's software stack is ready.
- Source: [neowin.net](https://www.neowin.net/news/computex-2026-intel-says-its-solved-one-of-the-biggest-physical-ai-and-robotics-issue/)

**Ambarella, Hailo, Rockchip, MediaTek:** *Nothing material this week.*

---

## 6. China Robotics Ecosystem

**Humanoid shipment rankings (H1 2026 data released ~Oct 1):**
- **AgiBot:** ~8,400 units, 44% global share — overtook Unitree for #1 global ranking.
- **Unitree:** ~5,900 units, 31% global share.
- **Global total:** 19,100 units in H1 2026, +272% YoY. Chinese vendors: ~97% of global output.
- Sources: [robotsbeat.com](https://robotsbeat.com/agibot-unitree-global-humanoid-shipments-19100-h1-2026-sag), [humanoidsdaily.com](https://www.humanoidsdaily.com/news/global-humanoid-shipments-surge-272-in-1h-2026-as-agibot-overtakes-unitree)

**Unitree IPO (context — Aug 2026):**
- Listed on Shanghai STAR Market Aug 19; +629% day-one pop; ~$50B post-debut market cap. Ticker: 688836. IPO raised ~$900M.
- Source: [Forbes](https://www.forbes.com/sites/jonmarkman/2026/08/18/unitree-starts-trading-tomorrow-in-shanghai-after-8000x-ipo-demand/)

**JAKA Kargo50 + Zu50 (CIIF, ~Oct 13) — see §2.** First wheeled humanoid from a Chinese cobot leader. JAKA EVO OS, cloud-connected, factory-floor focus.

**XPeng Iron:**
- Mass production targeted end-2026; first units to XPeng EV showrooms in China; overseas customer deliveries in 2027. CEO now directly running robotics unit.
- Source: [ifactoryapp.com](https://ifactoryapp.com/industries/manufacturing-plant/chinese-humanoid-manufacturing-agibot-xpeng-ubtech-byd)

**Government & policy:**
- No new MIIT action confirmed this week. Background: 300M yuan+ embodied-intelligence measures (Aug 2026); government targets 10,000+ humanoid deployments by end of 2026 across 100+ use cases. Source: [thnet.gov.cn](https://en.thnet.gov.cn/2026-08/03/c_1202047.htm)
- FCC import restriction risk flagged as ongoing threat to Chinese humanoid exports.

**Compute supply chain:**
- Black Sesame Huashan A2000 (7nm, automotive/robotics SoC) cleared US Department of Commerce review (Jan 2026) — only Chinese chipmaker to do so. Source: [SCMP](https://www.scmp.com/tech/article/3338742/chinese-automotive-chipmaker-black-sesames-huashan-a2000-clears-us-review-hurdle) (date via search index)
- No new Horizon Robotics, Cambricon, or Rockchip actions this week.

---

## 7. Policy / Standards / Safety

**EU AI Act — Digital Omnibus Deadline Clarification (Oct 13, 2026)**
- Stand-alone Annex III AI systems: obligations apply **Dec 2, 2027**.
- AI embedded in Annex I regulated products (covers most industrial/collaborative robots): **Aug 2, 2028**.
- Generative/general-purpose AI transparency rules: systems on market from Aug 2, 2026 must comply at launch; older systems grace period expires **Dec 2, 2026** — near-term compliance deadline.
- Source: [technology.org, Oct 13](https://www.technology.org/2026/10/13/eu-ai-act-deadlines-after-the-digital-omnibus-what-applies-from-december-2026-to-august-2028/)

**EU Machinery Regulation (EU) 2023/1230:** Replaces current Machinery Directive on **Jan 20, 2027** — covers AI and digital components in machinery. Robotics OEMs selling into EU market: ~3 months to deadline. Source: [robotops.pro](https://robotops.pro/blog/eu-ai-act-and-machinery-regulation-for-robots)

**EU Dual-Use Export Controls:** Commission updated the dual-use list Sept 14, 2026; AI hardware and GPU/accelerator systems now covered. Relevant to robot SoC supply chains. Source: [carraglobe.com](https://carraglobe.com/eu-dual-use-export-controls-it-ai-hardware/)

*No new ISO 10218 actions, FDA medical robot clearances, or NHTSA/OSHA actions confirmed this week.*

---

## 8. Conferences & Signals

**RoboBusiness 2026 (Oct 20–21, Santa Clara Convention Center)** — OPENS TOMORROW
- Keynotes: Rodney Brooks (Robust AI) + Jonathan Hurst (Agility) + Ken Goldberg (UC Berkeley) on "The Next 20 Years"; "Beyond the Demo: AI in Production" with Amazon; "State of Humanoids" with Agility, Apptronik, Persona AI, PSYONIC.
- Source: [therobotreport.com](https://www.therobotreport.com/learn-how-physical-ai-is-being-used-to-do-real-work-at-robobusiness/)

**Long Horizon Physical AI Summit (Oct 20–21, Fort Mason, San Francisco)** — OPENS TOMORROW
- Keynote: Deepak Pathak (Skild AI CEO). Speakers: Sebastian Thrun (Google X), Alex Kendall (Wayve). ~600 attendees, ~40 speakers.
- Source: [encord.com](https://encord.com/long-horizon/)

**Physical AI & Robotics Summit (Economist, London, Oct 13)** — COMPLETED
- Mythic (edge AI processor) on agenda. No public announcements confirmed.

**IROS 2026 (Pittsburgh, Sep 27–Oct 1)** — COMPLETED
- 7,000+ attendees; τ₀-VLA and other arXiv papers (Aug 2026) reflect IROS-cycle submissions. Source: [arxiv.org/abs/2608.16885](https://arxiv.org/abs/2608.16885)

---

## So What — Strategic Implications

1. **Physical Intelligence's Pi API is the week's strategic pivot.** Moving from a closed lab to a developer ecosystem mirrors OpenAI's GPT API expansion. The training-data flywheel (Mecka's $60M Sequoia raise feeds directly into this) could commoditize robot learning. Platform that controls inference infrastructure wins. Intel needs OpenVINO Physical AI GA *this quarter* to stay in this race.

2. **Qualcomm IQ10 at GA (September 2026) is the clearest near-term Intel pressure point.** 700 TOPS, industrial temperature rating, purpose-built robotics SoC — not a repurposed PC chip. Neura and potential Kuka design wins are meaningful. Intel's cost-advantage claim needs independent validation.

3. **NVIDIA Jetson Thor T2000/T3000 slip to Q1 2027 creates a narrow window for Intel.** Design wins decided in Q4 2026 before Thor ships may favor Intel if OpenVINO Physical AI GA lands on time. If it slips, Qualcomm fills the vacuum.

4. **Chinese humanoid scale is pulling decisively away from Western makers.** AgiBot + Unitree = ~75% of global H1 2026 humanoid shipments; Chinese vendors supply ~97% of the market. JAKA's Kargo50 extends the ecosystem into wheeled humanoids for factory floors. Western OEMs (BMW/Figure, Amazon/Agility) remain in pilot or single-digit-facility deployment.

5. **Watch RoboBusiness + Long Horizon (Oct 20–21) for 2027 deployment commitments.** Amazon and Agility sharing a keynote stage is the highest-signal moment of the week. Any publicly stated production volumes for 2027 would be the most decision-relevant data point to come out of these shows.

---

*Tags: funding · humanoids · foundation-models · silicon · china*
