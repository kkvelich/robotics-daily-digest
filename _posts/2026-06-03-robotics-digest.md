---
layout: post
title: "Robotics Brief — 2026-06-03"
date: 2026-06-03
tags: [funding, products, humanoids, foundation-models, silicon, china, policy, conferences]
---

# Robotics Market Sensing — 2026-06-03

> **Coverage window:** June 2–3, 2026 UTC. Items from June 1 (NVIDIA GTC Taipei pre-show) are included where they have confirmed June 2 follow-on coverage; dates are flagged explicitly. Direct WebFetch was blocked (HTTP 403) on most outlets; all claims are corroborated by ≥2 independent search-result snippets with encoded publication dates.

---

## TL;DR
- **NVIDIA dropped a full-stack open humanoid reference design at GTC Taipei/Computex**: Unitree H2 Plus chassis + Jetson AGX Thor T5000 (2,070 FP4 TFLOPS) + Sharpa tactile hands + GR00T N1.7 software — the clearest bid yet to own the physical-AI stack from silicon to model. GR00T N2 (2× task success rate) previewed for H2 2026.
- **Intel countered at its Computex keynote (June 2, Taipei)**: OpenVINO Physical AI Framework (open-source, runtime-agnostic), 130+ Core Ultra Series 3 design wins in edge robotics. Direct counter-narrative to NVIDIA lock-in, but Intel lacks a reference robot of its own.
- **Unitree's IPO cleared China's SSE listing committee June 2** — first "embodied AI" company greenlit for A-share; ¥4.2B (~$618M) raise at ~$6.2B valuation. Simultaneously: Unitree named as NVIDIA's GR00T reference hardware and opened Asia's first humanoid retail store in Shanghai.

---

## 1. Funding & M&A

| Company | Stage | Amount | Lead Investor | What They Build | Compute Platform | Source |
|---------|-------|--------|---------------|-----------------|------------------|--------|
| **Unitree Robotics** | IPO — SSE STAR Market listing-committee approval | ¥4.2B (~$618M) | Public market | Humanoid robots (H1, H2 Plus, G1), quadrupeds (Go2) | Jetson Thor (H2 Plus); proprietary motor controllers | [Caixin, June 2](https://www.caixinglobal.com/2026-06-02/humanoid-robot-maker-unitree-advances-toward-618-million-shanghai-ipo-102449940.html) |

> Registration, issuance, and pricing steps still ahead. Unitree posted ~¥600M adjusted net profit in 2025 (first profitable year, +674% YoY). 32.4% global humanoid market share by units.

*No VC rounds >$10M confirmed in the June 2–3 window at time of publication.*

---

## 2. Product Launches & Demos

- **NVIDIA Isaac GR00T Reference Humanoid Robot** — First open, full-stack reference design for humanoid research. Hardware: Unitree H2 Plus (6 ft / 150 lb / 31 DoF) + Sharpa Wave five-finger hands (22 DoF per hand; 75 DoF total). Silicon: **NVIDIA Jetson AGX Thor T5000** (2,070 FP4 TFLOPS). Software: Isaac GR00T open models + Isaac Lab. Target: Stanford, ETH Zurich, Ai2, UCSD. Available from Unitree late 2026. *(June 1 press release, June 2 wide coverage)* [[GlobeNewsWire, June 1]](https://www.globenewswire.com/news-release/2026/06/01/3303990/0/en/NVIDIA-Announces-NVIDIA-Isaac-GR00T-Reference-Humanoid-Robot-for-Academic-Research.html) [[CGTN, June 1]](https://news.cgtn.com/news/2026-06-01/NVIDIA-Unitree-unveil-new-humanoid-powered-by-Isaac-GR00T-1NCWlv6VRde/p.html)

- **Qualcomm Dragonwing IQ10 Robotics Reference Design** — Computex unveil (June 1–2). 700 TOPS on-device AI; 18 Qualcomm Oryon CPU cores + multicore NPU + GPU; native support for 12 GMSL2 cameras + LiDAR + ToF + IMU. Early access to customers **June 2026**; global GA **September 2026**. Positions directly against Jetson AGX Orin/Thor. [[The Gadgeteer, June 1]](https://the-gadgeteer.com/2026/06/01/qualcomm-computex-snapdragon-c-dragonwing-iq10-robotics/) [[HotHardware]](https://hothardware.com/news/qualcomm-unveils-dragonwing-iq10)

- **Intel OpenVINO Physical AI Framework** — Announced at Computex keynote (June 2, Taipei). Open-source inference runtime for physical AI on **Intel Core Ultra Series 3 (Panther Lake)**; 130+ design engagements confirmed. SensoryAI's "Ella" robot barista demo: three AI agents running simultaneously on a single chip. First open-source robotics library with silicon-optimized inference runtime. [[WindowsReport]](https://windowsreport.com/intel-unveils-openvino-physical-ai-platform-for-robots-drones-and-edge-ai-systems/) [[FierceSensors]](https://www.fiercesensors.com/sensors/intel-unveils-openvino-robots-130-firms-use-ultra-series-3)

---

## 3. Foundation Models & Software

- **NVIDIA Cosmos 3** *(launched at GTC Taipei, ~June 1)* — First open "Physical AI Omnimodel": natively generates text, image, video, ambient sound, and robot actions from a single model trained on 20T tokens. **Cosmos 3 Nano** (16B params: 8B reasoner + 8B generator) and **Cosmos 3 Super** (64B: 32B + 32B) available now; **Cosmos 3 Edge** (2B) for on-robot inference announced for later release. NVIDIA Cosmos Coalition formed with Agile Robots, Black Forest Labs, Skild AI, and Runway. [[HPCwire AIwire, June 1]](https://www.hpcwire.com/aiwire/2026/06/01/nvidia-launches-cosmos-3-the-open-frontier-foundation-model-for-physical-ai/) [[NVIDIA Newsroom]](https://nvidianews.nvidia.com/news/nvidia-launches-cosmos-3-the-open-frontier-foundation-model-for-physical-ai)

- **NVIDIA Isaac GR00T N1.7** *(early access)* — 3B-parameter open VLA (Cosmos-Reason2-2B backbone + 32-layer DiT action head), Apache 2.0 licensed. Powers the GR00T reference robot. GitHub + HuggingFace release imminent. [[NVIDIA Dev Forum]](https://forums.developer.nvidia.com/t/early-access-isaac-gr00t-n1-7-open-reasoning-vla-model-for-humanoid-robotics/366916) [[HuggingFace blog]](https://huggingface.co/blog/nvidia/gr00t-n1-7)

- **NVIDIA GR00T N2** *(preview)* — Based on DreamZero research; claimed >2× task-success rate vs. leading VLA models in novel environments. No public weights; ETA end-2026. Watch for ICRA 2026 workshop presentations on underlying research. [[BGR]](https://www.bgr.com/2186074/nvidia-2026-computex-announcements-dlss-rtx-spark/)

- **NVIDIA JetPack 7.2** *(announced Computex)* — Key robotics features: **MIG (Multi-Instance GPU) on Jetson Thor** for deterministic multiworkload isolation; **CUDA 13 on Jetson Orin**; one-command **NemoClaw agentic AI** deploy; official **Yocto Project** support for production builds. Built on Linux Kernel 6.8 / Ubuntu 24.04 LTS. [[AI Weekly]](https://aiweekly.co/alerts/nvidia-jetpack-72-adds-mig-and-241-tops-to-edge-ai) [[NVIDIA Blog]](https://blogs.nvidia.com/blog/jetson-agentic-ai-physical-world/)

---

## 4. Customer Deployments

*Nothing material today.*

---

## 5. Competitive Silicon Watch ⚠️

- ⚠️ **Qualcomm Dragonwing IQ10** — **700 TOPS**, 18 Oryon cores, all-in-one sensor architecture (12 GMSL2 cameras native). Early-access customer shipments **this month**; GA September. The integrated compute+sensing BOM collapse is the core threat to both NVIDIA Jetson and Intel edge modules. Pressures Intel's robotics design-win pipeline directly. [[The Gadgeteer, June 1]](https://the-gadgeteer.com/2026/06/01/qualcomm-computex-snapdragon-c-dragonwing-iq10-robotics/)

- **NVIDIA Jetson AGX Thor T5000** — Inside NVIDIA's GR00T reference design (2,070 FP4 TFLOPS). JetPack 7.2 MIG support makes it viable for production multi-tenant robotics workloads. NVIDIA's reference-robot strategy converts developer adoption directly into silicon pull. [[NVIDIA Newsroom]](https://nvidianews.nvidia.com/news/nvidia-open-humanoid-robot-reference-design)

- ⚠️ **Intel Core Ultra Series 3 / OpenVINO Physical AI** — 130+ design engagements at Computex, but the open-source / silicon-agnostic pitch is a defensive posture, not a pull motion. The Ella barista demo (multi-agent on one chip) is the clearest Intel commercial proof point in robotics so far. Key question: can Intel get a reference humanoid partner the way NVIDIA got Unitree? [[Intel Newsroom]](https://newsroom.intel.com/artificial-intelligence/intel-announces-new-ai-innovations-at-computex) [[Blockonomi]](https://blockonomi.com/intel-intc-stock-drops-despite-computex-2026-reveals-xeon-6-and-ai-infrastructure-launch/)

- **MediaTek Genio 720 / 520** — Genio 720 powering PRIMAX AMR300 (multi-robot collaboration); Genio 520 powering NUWA Kebbi3 embodied AI. Shown at Computex Robotics & Physical AI Pavilion — MediaTek gaining AMR/embodied foothold in mid-tier cost bands. [[MediaTek Computex 2026]](https://www.mediatek.com/computex2026)

- **Rockchip (via Aetina)** — Aetina DeviceEdge AIE-KR1B-B1 with Rockchip processor shown at Computex for edge robotics/vision AI. Signals continued Rockchip OEM traction at sub-Jetson price points. [[RoboticsTomorrow]](https://www.roboticstomorrow.com/news/2026/05/21/aetina-demonstrates-edge-ai-platforms-for-robotics-vision-ai-and-enterprise-automation-at-computex-2026/26605/)

---

## 6. China Robotics Ecosystem

**Humanoids:**
- **Unitree IPO cleared** — Shanghai Stock Exchange listing committee approved June 2. First "embodied AI" company on China's A-share STAR Market. ¥4.2B (~$618M) target; ~$6.2B valuation. IPO cleared in 73 days from formal acceptance — unusually fast. NVIDIA simultaneously named Unitree H2 Plus as its GR00T reference chassis, giving Unitree dual Western-research + China-capital validation on the same week. [[Caixin, June 2]](https://www.caixinglobal.com/2026-06-02/humanoid-robot-maker-unitree-advances-toward-618-million-shanghai-ipo-102449940.html) [[TradingView/Reuters]](https://www.tradingview.com/news/reuters.com,2026:newsml_L4N4290LN:0-unitree-s-ipo-approved-by-shanghai-stock-exchange-s-listing-review-committee/)

- **Unitree opens Asia's first "Embodied Intelligence Experience Hall"** (June 1–2, Jing'an, Shanghai) — 100+ sqm in Jiuguang Department Store on West Nanjing Road; sells G1/R1 humanoids and Go2 quadrupeds direct-to-consumer. Orders placed on opening day. CEO 2026 guidance: 10,000–20,000 unit deliveries. [[Xinhua, June 1]](https://english.news.cn/20260601/07967c3ecf6048aa86e6f2a295076f97/c.html) [[Robotics.sg, June 2]](https://robotics.sg/2026/06/02/unitree-to-open-asias-first-embodied-intelligence-experience-store-in-shanghai/)

**Industrial / Cobot:** *Nothing material June 2–3.*

**Compute & Supply Chain:**
- MediaTek Genio 720 confirmed inside PRIMAX AMR300 at Computex — visible mid-tier Chinese-chip gains in the AMR segment. [[MediaTek]](https://www.mediatek.com/computex2026)

**Policy:**
- **2026 Shenyang Robot Conference** (opened June 1, covered June 3) — Theme: "New Quality Productive Forces Driving Development, Intelligent Manufacturing Connecting the Future." Key formations: (1) **Liaoning Embodied Intelligence Industrial Technology Innovation Alliance** inaugurated; (2) **Northeast Asia Embodied Intelligence Innovation Center** launched. Shenyang's robotics + intelligent-manufacturing cluster designated a national advanced manufacturing cluster. [[Manila Times / GlobeNewswire, June 3]](https://www.manilatimes.net/2026/06/03/tmt-newswire/globenewswire/2026-shenyang-robot-conference-opens/2357860)

**Deployments:** *Nothing confirmed June 2–3.*

---

## 7. Policy / Standards / Safety

- **White House EO: "Promoting Advanced Artificial Intelligence Innovation and Security"** *(signed June 2, 2026)* — Key provisions: (1) Frontier AI developers asked to **voluntarily submit powerful models for up to 30-day government review** before public release; (2) Directs creation of a federal **AI cybersecurity clearinghouse**; (3) Hardening of NSS and civilian agency AI systems. No explicit robotics export-control language. **Watch**: if the 30-day review mechanism becomes mandatory or gains robotics-specific carve-outs, VLA/foundation model deployment timelines for dual-use robot platforms (defense logistics, autonomous manipulation) will be affected. [[NPR, June 2]](https://www.npr.org/2026/06/02/nx-s1-5844347/ai-safety-trump-executive-order) [[White House Fact Sheet, June 2]](https://www.whitehouse.gov/fact-sheets/2026/06/fact-sheet-president-donald-j-trump-promotes-advanced-artificial-intelligence-innovation-and-security/)

---

## 8. Conferences & Signals

- ⚠️ **Computex 2026** (Taipei, **June 2–4**, ongoing) — This is the highest-density silicon/edge-AI signal session of the 24h window. New this year: dedicated **Robotics & Physical AI Pavilion** with OEM demos. Confirmed robotics/edge-AI keynote announcements: Intel OpenVINO Physical AI (June 2), NVIDIA Cosmos 3 + JetPack 7.2 (June 1 pre-show), Qualcomm IQ10 (June 1), MediaTek Genio AMR demos. Cross-references Section 5 for all chip details. [[Tom's Hardware Live]](https://www.tomshardware.com/news/live/computex-2026-) [[Intel Computex]](https://www.intel.com/content/www/us/en/events/computex.html)

- **ICRA 2026** (Vienna, **June 1–5**, ongoing) — 43rd IEEE International Conference on Robotics and Automation; theme "Robots for all." NVIDIA has a featured keynote + accepted papers + workshops. Competitions in window: Picking in Clutter (June 2), Cloud Robotics (June 3). ICRA is where GR00T N1.7 academic follow-on is most likely to surface first. [[ICRA 2026]](https://2026.ieee-icra.org/) [[NVIDIA at ICRA]](https://forums.developer.nvidia.com/t/nvidia-at-icra-2026/371641)

- **2026 Shenyang Robot Conference** (Shenyang, **June 1–3**) — China's 9th annual industrial-robotics policy forum; see Section 6 for policy items. [[GlobeNewsWire/Manila Times, June 3]](https://www.manilatimes.net/2026/06/03/tmt-newswire/globenewswire/2026-shenyang-robot-conference-opens/2357860)

---

## So What — Strategic Implications

1. **NVIDIA's reference-robot play is the most consequential edge-AI move of the week.** By bundling Cosmos 3 + GR00T N1.7 + Jetson AGX Thor T5000 into a single purchasable research platform, NVIDIA converts developer adoption at Stanford and ETH Zurich into silicon pull at scale. Every lab that builds workflows on GR00T defaults to Jetson. **Intel's hybrid-edge story needs an equivalent anchor hardware partner — urgently.**

2. **Qualcomm IQ10 at 700 TOPS with integrated sensor architecture is the sharpest near-term threat to Intel's edge-robotics design-win pipeline.** The IQ10's BOM-collapse pitch (compute + 12-camera + LiDAR in one design) undermines the multi-chip hybrid-edge configurations where Intel Core Ultra chips currently win. Watch September GA customer announcements.

3. **Unitree's IPO + NVIDIA selection + retail store is a de-facto-standard signal for the humanoid body market.** If the H2 Plus becomes the "reference torso" for Western researchers the way Arduino became a reference MCU, Unitree captures margins at the hardware layer while NVIDIA captures them at the silicon/software layer. Competing robot body makers (Figure, Agility, 1X) need differentiated software partnerships fast.

4. **The White House AI EO's voluntary review mechanism is low-urgency but worth registering in roadmaps.** VLAs with military logistics or dual-use manipulation applications may face pre-launch review windows. Start documenting model use-case scope in safety datasheets now, before the mechanism potentially becomes mandatory.
