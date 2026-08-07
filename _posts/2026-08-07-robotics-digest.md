---
layout: post
title: "Robotics Brief — 2026-08-07"
date: 2026-08-07
tags: [funding, humanoids, foundation-models, deployments, silicon, china]
---

# Robotics Market Sensing — 2026-08-07

## TL;DR
- **Unitree prices China's first mainland humanoid IPO at $9B** — DeepSeek takes $20.8M strategic stake + a mutual AI-preference pact; the most consequential robotics capital-markets event of the year.
- **HII signs up to $900M in production agreements with Path Robotics & GrayMatter Robotics** to automate U.S. Navy shipbuilding — the largest named-customer robotics deployment contract of 2026.
- **Hadrian closes $1.37B Series D at $7.87B** to scale AI/robotics U.S. defense manufacturing; Xiaomi open-sources its first VLA (Xiaomi-Robotics-1) with 100K+ hours of training data.

---

## 1. Funding & M&A

| Company | Stage | Amount | Lead investor | What they build | Compute | Source |
|---|---|---|---|---|---|---|
| Unitree Robotics | IPO (STAR Market) | ¥6.1B / $904M | Public; DeepSeek + PetroChina strategic | Humanoid & quadruped robots | Undisclosed | [Bloomberg, Aug 6](https://www.bloomberg.com/news/articles/2026-08-06/china-s-unitree-seeks-904-million-in-first-mainland-robotic-ipo) |
| Hadrian | Series D | $1.37B | WCM, Washington Harbour, Valor Equity, 137 Ventures, Baillie Gifford; JPMorganChase co-lead | AI/robotics defense & aerospace precision factories | Undisclosed | [Axios, Aug 6](https://www.axios.com/2026/08/06/hadrian-series-d-defense-production) |
| Path Robotics | Contract (HII) | Up to $600M | HII (Navy programs, 7-yr) | Autonomous AI welding robots | Undisclosed | [GlobeNewswire, Aug 6](https://www.globenewswire.com/news-release/2026/08/06/3340512/14858/en/hii-signs-performance-based-production-agreements-with-path-robotics-and-graymatter-robotics.html) |
| GrayMatter Robotics | Contract (HII) | Up to ~$300M | HII (Navy programs, 7-yr) | Physical AI for grinding, painting, assembly, inspection | Undisclosed | [GlobeNewswire, Aug 6](https://www.globenewswire.com/news-release/2026/08/06/3340512/14858/en/hii-signs-performance-based-production-agreements-with-path-robotics-and-graymatter-robotics.html) |

**Unitree IPO**: 150.80 yuan/share, 219× P/E. DeepSeek allocated 933K shares (3-yr lockup) + mutual preference pact (DeepSeek gets preferred AI model training from Unitree; Unitree gets preferred robot purchases from DeepSeek). PetroChina also in strategic placement. Subscriptions Aug 10. Revenue ¥1.7B in 2025 (4× YoY); humanoids now largest business. Also: [CNBC Aug 6](https://www.cnbc.com/2026/08/06/chinese-humanoid-robot-maker-unitree-prices-ipo-at-9-billion-valuation.html) · [Caixin Aug 7](https://www.caixinglobal.com/2026-08-07/unitree-robotics-prices-shanghai-ipo-at-61-billion-yuan-valuation-102472090.html) · [TechNode Aug 7](https://technode.com/2026/08/07/deepseek-takes-rmb141-million-strategic-placement-in-unitree-ipo/)

**HII deal**: Navy aircraft carriers, submarines, destroyers, frigates, unmanned surface vessels. Two-stage structure: (1) develop/validate automation tech, (2) source production contingent on cost/schedule/quality. Part of HII's HYPR (High-Yield Production Robotics) program. [Robot Report](https://www.therobotreport.com/hii-signs-up-to-900m-agreement-with-path-robotics-graymatter-robotics/)

**Hadrian**: Also backed by a16z, Founders Fund, Lux, Apollo, T. Rowe Price. Valuation up from $1.6B in Jan 2026; ~3M sq ft across 4 factory sites. Proprietary "Opus" software platform.

---

## 2. Product launches & demos

- **BYD "Xiao Di" humanoid** — 1.61m, 58.5kg, 31 DoF; real-time translation across 6 Chinese dialects + 6 foreign languages. Now deployed at Di Space showroom, Zhengzhou; targeting 2–3 units per dealership. Silicon: undisclosed. [(Interesting Engineering)](https://interestingengineering.com/ai-robotics/byd-enters-humanoid-robot-race-with-august-debut) (date via search index)
- **Foxconn humanoid at NVIDIA GTC 2026** — Features SEER Robotics "robot brain" controller. Foxconn targets 5,000 robots deployed by end-2026. Silicon: NVIDIA stack. [(OpenPR, Aug 7)](https://www.openpr.com/news/4598045/foxconn-humanoid-robot-featuring-seer-robotics-robot-brain) (date via search index)
- **Animotion Robotics "Éloi"** — Bionic social companion with modular magnetic face (swappable eyes/nose/mouth/skin), proprietary on-device "personality chip" that accumulates interaction data without cloud. Cofounded by Shane Zhu (ex-Disney Imagineering) and David Holz (Midjourney). Hardware not yet shipping ("Dream State" digital phase). Silicon: proprietary onboard AI chip (undisclosed). [(PRNewswire, Aug 7)](http://www.prnewswire.com/news-releases/animotion-robotics-unveils-eloi-the-first-bionic-robot-redefining-the-interpersonal-bond-between-humans-and-machines-302845834.html) (date via search index)

---

## 3. Foundation models & software

- **Xiaomi-Robotics-1** (open-sourced Aug 3–5, borderline 24h): MoT architecture — Qwen3-VL vision-language backbone + Diffusion Transformer action head. Pre-trained on 100,000+ hours real manipulation trajectories across 1,700+ scenarios; post-trained on 10,000+ hours cross-embodiment data. Tops RoboDojo and RoboCasa365 benchmarks. Full open-source: code, weights, training pipeline. No performance saturation observed at scale — the first VLA to demonstrate scaling-law behavior at this data volume. [(GitHub)](https://github.com/XiaomiRobotics/Xiaomi-Robotics-1) · [(TechNode, Aug 5)](https://technode.com/2026/08/05/xiaomi-open-sources-embodied-ai-foundation-model-xiaomi-robotics-1/) (date via search index)
- **ROS 2 Rolling nightly** — Aug 6 nightly binary build shipped across all supported OS targets. No named release; rolling channel carries the bleeding-edge stack. [(GitHub ros2/ros2)](https://github.com/ros2/ros2/releases)

---

## 4. Customer deployments

- **U.S. Navy / HII** — Path Robotics and GrayMatter Robotics contracted for up to $900M over 7 years to automate welding, grinding, blasting, painting, and inspection on carrier, submarine, and destroyer production lines. First milestone-gated performance-based robotics deal at this scale in U.S. defense. (See §1 for detail.)
- **Serve Robotics Q2 2026** (SEC 8-K, Aug 6): 2,000 sidewalk robots across 44 cities / 6 metro areas. Revenue $3.24M (+405.9% YoY). **Guidance cut**: FY2026 revised to $9–10M (from $26M) on Uber Eats volume shortfall; DoorDash + hospital contracts (7 renewals + 2 new) partially offset. Cash: $240.4M. [(SEC 8-K)](https://www.sec.gov/Archives/edgar/data/0001832483/000183248326000034/serv-20260806.htm)

---

## 5. Competitive silicon watch ⚠️

- **Black Sesame Technologies (9767.HK)** — CEO Shan Jizhang voluntarily extended lock-up on 44.1M shares (6.18%) from Aug 7, 2026 → Aug 7, 2027. Pivot: on-device AI inference across automotive (Huashan A2000/A1000 SoCs) + embodied intelligence (Wudang C1236/C1296). ⚠️ China's automotive-grade edge SoC player is betting car and robot inference converge — direct overlap with Intel Core Ultra NPU positioning. [(TipRanks)](https://www.tipranks.com/news/company-announcements/black-sesame-founder-extends-lock-up-to-back-on-device-ai-strategy) (date via search index)

**Prior-week context (outside 24h, high-signal):** AMD Ryzen AI Embedded X100 (July 24) — 50 TOPS NPU, −40°C industrial rating, Strix Halo APU targeting robots directly; direct Intel Core Ultra Series 3 rival for edge robotics. [(Tom's Hardware)](https://www.tomshardware.com/pc-components/cpus/amds-new-x100-chip-lineup-puts-strix-halo-into-robots-apus-for-physical-ai-bring-zen-5-cpu-rdna-3-5-gpu-cores-to-compete-with-intels-panther-lake) · Microchip acquires Hailo (July 24): Hailo-10H (40 TOPS / 2.5W) enters Microchip's embedded ecosystem. [(GlobeNewswire)](https://www.globenewswire.com/news-release/2026/07/24/3333099/0/en/Microchip-Technology-Signs-Definitive-Agreement-to-Acquire-Hailo.html) · NVIDIA Jetson T3000/T2000 (July 15): Blackwell-based mainstream robot modules, 865 / 400 FP4 TFLOPS, hardware ships Q1 2027. [(NVIDIA Blog)](https://blogs.nvidia.com/blog/jetson-thor-robotics-edge-ai-agent/)

---

## 6. China robotics ecosystem

- **Humanoids**: Unitree IPO dominates (see §1 + §5). BYD Xiao Di on floor at Di Space (see §2). AgiBot HK IPO ongoing: $5.1–6.4B target valuation, CICC + CITIC + Morgan Stanley underwriting, 15K units shipped. [(CryptoBriefing)](https://cryptobriefing.com/agibot-hong-kong-ipo-humanoid-robotics/)
- **Industrial / cobot**: *Nothing material today.*
- **Compute & supply chain**: DeepSeek-Unitree pact wires China's top LLM lab into the top robot maker — mirrors NVIDIA Isaac/GR00T vertical at national-ecosystem scale. Black Sesame lock-up extends (see §5).
- **Policy**: FCC Covered List (July 28) bans new FCC authorizations for foreign humanoids/AMRs — directly targets Unitree, Pudu, Keenon US exports. MIIT's 100K-humanoid-by-2027 target is the domestic demand floor.
- **Deployments**: Foxconn humanoid at NVIDIA GTC (see §2).

---

## 7. Policy / standards / safety

- **FCC Covered List** (July 28 ruling; legal analysis ongoing this week): Foreign-produced humanoids, quadrupeds, and networked AMRs >2 kg banned from new FCC equipment authorization. Existing authorized models grandfathered. Affects Unitree, Pudu, Keenon, BYD Xiao Di US entry. [(FCC DA-26-786)](https://www.fcc.gov/document/fcc-adds-foreign-produced-power-inverters-and-robots-covered-list-0) · [(K&L Gates, Aug 3)](https://www.klgates.com/thought-leadership/FCC-Adds-Foreign-Produced-Advanced-Robotic-Devices-to-the-Covered-List-Five-Things-to-Know-8-3-2026) · [(Morgan Lewis)](https://www.morganlewis.com/pubs/2026/08/fcc-adds-foreign-produced-advanced-robotic-devices-and-power-inverters-to-covered-list-opens-conditional-approval-process)
- **EU AI Act**: Full transparency + GPAI enforcement active since Aug 2. Robotics / high-risk product rules deferred to Dec 2, 2027. [(EU Commission)](https://ec.europa.eu/commission/presscorner/detail/en/ip_26_1714)

---

## 8. Conferences & signals

- **World Robot Conference 2026** (Beijing, Aug 19–23) — 12 days out. 300+ exhibitors, 2,000+ exhibits, 150+ product launches expected. Chinese humanoid OEMs likely to use as platform for production-scale commitments. [(Beijing gov)](https://english.beijing.gov.cn/beijinginfo/sci/event/202607/t20260710_4756514.html)
- **Hot Chips 38** (Stanford, Aug 23–25) — Key silicon watch event; ~25 presentations from NVIDIA, AMD, Intel, Google, Apple chip architects. Immediately follows WRC — will mirror the robot-stack story with a silicon lens. [(Hot Chips)](https://hotchips.org/)
- **Actuate 26** (San Francisco, Aug 18–19) — Robotics developer conference, 11 days out.
- **DARPA Lift Challenge Finals** (Aug 6–9, USAF Museum, Dayton OH, **ongoing now**) — 100+ teams compete for up to $6.5M; target 4× payload-to-weight ratio for autonomous aerial vehicles. Watch for edge compute stack disclosures. [(DARPA)](https://www.darpa.mil/news/2026/meet-lift-challenge-teams)

---

## So what — strategic implications

- **The HII/$900M deal reframes defense robotics economics.** Performance-based, milestone-gated contracts at this scale are new. Path Robotics (AI welding) and GrayMatter (physical AI for grinding/painting) now have a 7-year runway funded by the U.S. Navy. This validates the SWaP-C edge compute case for shipyard robotics — autonomy must run close to the work, not in the cloud.
- **The DeepSeek-Unitree pact is China's answer to NVIDIA Isaac/GR00T.** National AI model lab + top robot OEM = a preferential integration stack. Watch whether Baidu, Alibaba, or ByteDance replicate this with other Chinese robot makers.
- **Xiaomi-Robotics-1 is the first open VLA showing no scaling saturation at 100K+ hours.** If the scaling law holds, this means the open-weight VLA ecosystem will rapidly close the gap on proprietary models — compressing the moat for closed-stack vendors.
- **Serve Robotics' guidance cut is the most useful deployment-economics data in months.** +406% YoY revenue but FY cut in half on one customer volume shift. At-scale robot deployment revenue is still fragile — fleet-level data moats matter more than unit count.
- **Watch WRC Beijing + Hot Chips in the next 2 weeks.** These two events together will define the edge-compute narrative heading into 2027 procurement cycles — Chinese OEMs on the robot side, silicon architects on the chip side.
