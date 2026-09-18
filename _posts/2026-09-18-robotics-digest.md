---
layout: post
title: "Robotics Brief — 2026-09-18"
date: 2026-09-18
tags: [funding, silicon, humanoids, china, deployments]
---

# Robotics Market Sensing — 2026-09-18

## TL;DR
- **NVIDIA Jetson Orin Nano 2 ships today** — 78 TOPS, 2× inference perf, 40% lower power at 15W. Direct threat to Qualcomm Dragonwing and Hailo at entry-level edge robotics.
- **D-Robotics closes $400M Series C** — China's leading robot-chip stack (Sunrise SoC + full dev platform) is now the best-funded non-NVIDIA edge-robotics silicon play globally.
- **Tesla Optimus supplier audit live in Ningbo** — teams arrived Sep 16, placing orders with 7 Tier-1 Chinese suppliers; 1,000 units/week target by late September signals real production intent.

---

## 1. Funding & M&A

| Company | Stage | Amount | Lead Investor | What they build | Compute platform | Source |
|---|---|---|---|---|---|---|
| D-Robotics (China) | Series C | $400M | Mirae Asset | Sunrise™ robot SoCs + full HW/SW stack for embodied AI | Proprietary Sunrise chip family | [PR Newswire APAC](https://en.prnasia.com/releases/apac/d-robotics-completes-400-million-in-series-c-funding-driving-the-robotics-industry-into-a-boom-in-product-categories-548285.shtml) (date via search index) / [Finsmes](https://www.finsmes.com/2026/09/d-robotics-raises-400m-in-series-c-funding.html) |
| AMC Robotics (Canada) | Equity SEPA | Up to $50M | Undisclosed | Robotic manufacturing facility buildout | Not disclosed | [GlobeNewswire](https://www.globenewswire.com/news-release/2026/09/18/3364686/0/en/amc-robotics-enters-into-standby-equity-purchase-agreement-to-provide-up-to-50-million-of-funding-to-accelerate-commissioning-of-its-robotic-manufacturing-facility.html) |

**D-Robotics context:** Mirae Asset led; Meituan, Hefei State-owned Capital, and Nanshan Zhixin joined. Funds target Sunrise chip portfolio expansion across all compute levels and a full software platform covering data collection → training → simulation → deployment. H1 2026 revenue grew several times YoY; cumulative Sunrise shipments >8M units.

---

## 2. Product Launches & Demos

- **NVIDIA Jetson Orin Nano 2** — Entry-level edge robotics computer. 78 TOPS AI compute, 8GB LPDDR5X-7500, 8-core Arm CPU, 15W TDP (2× inference performance over predecessor at 40% lower power in the same form factor). Early adopters: Cognex, Doosan Bobcat, Matic. Targets robots, drones, and vision AI. Silicon: NVIDIA Ampere GPU + Arm CPU. [NVIDIA Newsroom](https://nvidianews.nvidia.com/news/nvidia-announces-jetson-orin-nano-2-robotics-computer-to-redefine-entry-level-edge-ai) / [Robotics & Automation News](https://roboticsandautomationnews.com/2026/09/18/nvidia-unveils-jetson-orin-nano-2-for-robotics-and-edge-ai/104918/) / [ServeTheHome](https://www.servethehome.com/nvidia-announces-jetson-orin-nano-2-entry-level-edge-board-gets-new-ampere-silicon/)

---

## 3. Foundation Models & Software

*Nothing material today.*

---

## 4. Customer Deployments

- **Tesla Optimus / Ningbo supply chain** — Tesla dispatched its robotics team to Ningbo Sep 16; production audit started Sep 17 covering 7 Tier-1 Chinese suppliers (Tuopu Group actuators, Ningbo Joyson sensors, Zhejiang Sanhua thermal mgmt). Goal: transfer manufacturing capability from US factories to Chinese suppliers, hit 1,000 units/week by late September, 2,000–2,500/week by year-end, 50,000 total in 2026. Solactive China Humanoid Robotics Index +2.4%. [Bloomberg](https://www.bloomberg.com/news/articles/2026-09-18/chinese-robotics-suppliers-rise-on-tesla-optimus-audit-report) (date via search index) / [KuCoin](https://www.kucoin.com/news/flash/tesla-launches-production-audit-for-optimus-robots-in-china-aiming-for-50-000-units-by-2026) / [Moomoo](https://www.moomoo.com/community/feed/on-september-16-tesla-dispatched-its-robotics-team-to-ningbo-117288351105030)

- **Locus Robotics / Kimball Midwest** — 100+ AMRs across 3 US DCs (Ohio, Texas, Nevada); 13.2M robotic-assisted pick lines, 2× putaway productivity, ROI in <1 year. Recognized at 2026 Supply Chain Excellence Awards USA (Sep 15). Compute: Locus proprietary platform. [RoboticsTomorrow](https://www.roboticstomorrow.com/news/2026/09/18/locus-robotics-and-kimball-midwest-win-2026-supply-chain-excellence-award-for-best-use-of-robotics/27122/)

---

## 5. Competitive Silicon Watch ⚠️

- **NVIDIA Jetson Orin Nano 2** ⚠️ *Intel pressure* — 78 TOPS at 15W in a compact form factor with the full Isaac/ROS 2 software stack and 3M+ developer ecosystem. This directly undercuts the Intel Core Ultra Series 3 (NPU-augmented) value proposition at the entry-level robotics price point. NVIDIA can now offer 2× inference improvement with lower BOM power cost than the previous generation. [NVIDIA Newsroom](https://nvidianews.nvidia.com/news/nvidia-announces-jetson-orin-nano-2-robotics-computer-to-redefine-entry-level-edge-ai) / [ServeTheHome](https://www.servethehome.com/nvidia-announces-jetson-orin-nano-2-entry-level-edge-board-gets-new-ampere-silicon/)

- **D-Robotics Sunrise** — $400M Series C (see §1) accelerates Sunrise chip roadmap. With >8M units shipped and H1 revenue growing several times YoY, this is the only vertically integrated China-domestic alternative to NVIDIA Jetson at scale. [Finsmes](https://www.finsmes.com/2026/09/d-robotics-raises-400m-in-series-c-funding.html)

*No new Qualcomm, Hailo, Ambarella, Rockchip, or MediaTek announcements confirmed in the 24h window.*

---

## 6. China Robotics Ecosystem

- **Humanoids**: Spirit AI (300-person, >$670M raised) founder Gao Yang stated Sep 18 that "robot brains" will reach a ChatGPT-scale breakthrough by mid-2027, enabled by real-world (not sim) training data. Current milestone: 90% task success rate in structured home environments. Bottleneck cited: data scarcity, not model architecture. [Express Tribune](https://tribune.com.pk/story/2630041/founder-of-chinese-startup-spirit-ai-says-robot-brains-set-for-2027-breakthrough) / [CP24](https://www.cp24.com/news/2026/09/18/chinese-robot-brain-startup-sees-chatgpt-style-breakthrough-as-soon-as-next-year/)

- **Industrial / cobot**: No new announcements in 24h window.

- **Compute & supply chain**: D-Robotics $400M Series C closes (see §1 & §5). Tesla Optimus audit activates Tuopu, Joyson, Sanhua as Tier-1 supply chain (see §4).

- **Policy**: MIIT/SASAC "real-world training action" targets 10,000 humanoid deployments and 100 validated high-value applications by year-end 2026. Standing policy — no new announcement today. [PolicCN](https://policycn.com/public/commentaries/real-world-training-drive-targets-mass-robot-deployment-59090)

- **Deployments**: Tesla Optimus Ningbo production audit (see §4); UBTECH's new 14,000m² Liuzhou factory (commissioned Sep 12, >10,000 robots/year capacity, 10-min takt) entering full production ramp. [IBTimes](https://www.ibtimes.co.uk/chinas-humanoid-robots-scale-commercial-production-1819960)

---

## 7. Policy / Standards / Safety

- **EU AI Act** — November 2, 2026 deadline for transparency obligations applies to all AI system deployers, including robotics. No new guidance issued today. [HIAI Design](https://www.hiai-design.com/blog-eu-ai-act-robotics-2026)

*Nothing else material today.*

---

## 8. Conferences & Signals

- **IROS 2026** — Pittsburgh, PA; opens September 27. No pre-conference announcements in today's window.
- **IEEE-RAS Humanoids 2026** — December 6–9, Santa Clara, CA. CFP closed; program TBD.

*No active robotics or silicon events with material announcements today.*

---

## So What — Strategic Implications

1. **Jetson Orin Nano 2 resets the entry-level edge-robotics cost curve.** 78 TOPS at 15W for ~$150 module price is a direct challenge to Intel Core Ultra Series 3 NPU play at the same wattage tier. Intel's hybrid-edge story needs differentiation beyond raw TOPS — openness, x86 compatibility, and deterministic latency are still advantages, but the gap is narrowing fast.

2. **D-Robotics at $400M is the China-domestic Jetson.** With 8M+ Sunrise chips shipped and a full data-to-deploy software stack, it is positioned as the compute backbone for Chinese humanoid OEMs who want supply-chain independence from NVIDIA. Watch for Horizon Robotics ecosystem lock-in to compete with Isaac in China market.

3. **Tesla Optimus Ningbo audit is the most consequential supply-chain signal this week.** Transferring manufacturing IP to Chinese Tier-1 suppliers for 1,000 units/week by end of September means Optimus BOM cost will compress fast. This sets a price floor that pressures every other humanoid OEM's SWaP-C story.

4. **Spirit AI's "data bottleneck" claim is the key foundation-model signal to watch.** If real-world training data (not simulation) is the true scarcity, it favors vertically integrated players (Tesla, UBTECH, AgiBot) with large real-robot fleets over software-first labs. Watch whether Physical Intelligence's open-data strategy or NVIDIA GR00T synthetic-data pipeline gets traction as an alternative.
