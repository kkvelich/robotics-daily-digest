---
layout: post
title: "Weekly Deep Dive — 2026-06-28"
date: 2026-06-28
tags: [weekly, funding, deployments, humanoids, silicon, conferences]
---

# Weekly Robotics Deep Dive — Week of 2026-06-28

## TL;DR
- **Agility Robotics is going public** via a $2.5B SPAC merger with Churchill Capital XI, with $620M gross proceeds and >$300M in Digit v5 multi-year orders already in hand ([source](https://theaiinsider.tech/2026/06/24/agility-robotics-to-go-public-through-2-5-billion-merger-with-spac-churchill-capital-corp-xi/)).
- **BMW expanded Figure 03 to Spartanburg logistics** after Figure 02 helped build 30,000+ X3s — humanoid scope moves from body shop to assembly-line sequencing ([source](https://theaiinsider.tech/2026/06/26/bmw-to-use-figure-ais-figure-03-for-logistics-work-at-us-factory/)).
- **Automate 2026** (Chicago, June 22–25) was the inflection point: dedicated NVIDIA-sponsored Humanoid Pavilion, Figure BotQ hitting ~1 robot/hour, Boston Dynamics shipping electric Atlas, Digit running real Toyota shifts ([source](https://humanoid.guide/automate-2026-humanoid-robots/)).
- **China's deployment narrative goes live**: AGIBOT ran a six-day public livestream (June 23–28) of multiple humanoids on Longcheer's Nanchang tablet production line — directly executing on the MIIT/SASAC 10,000-unit mandate ([source](https://www.agibot.com/article/231/detail/79.html)).
- **Germany blinks**: VDMA + automatica survey shows 82% of German industry leaders want China-style subsidies for humanoid robotics — first explicit pressure on Berlin to respond ([source](https://www.roboticstomorrow.com/news/2026/06/26/german-economy-calls-for-faster-humanoid-robotics-adoption/26778/)).

## 1. Funding & M&A

| Company | Stage | Amount | Lead | What they build | Compute | Source |
|---|---|---|---|---|---|---|
| Agility Robotics | SPAC merger (CCXI → "AGLT") | $2.5B EV / $620M gross / $200M PIPE | Churchill Capital XI | Digit humanoid for warehouse/logistics | NVIDIA-aligned training stack | [TheAIInsider](https://theaiinsider.tech/2026/06/24/agility-robotics-to-go-public-through-2-5-billion-merger-with-spac-churchill-capital-corp-xi/) |

A relatively quiet funding week in the run-up to Automate — most cash deployed earlier in Q2 (Apptronik's $520M in February, Skild's $1.4B in January). The Agility transaction matters for one reason: it puts the first pure-play humanoid name on US public markets, giving silicon vendors a public comparable to anchor their robotics TAM stories.

## 2. Product launches & demos

Automate 2026 was the news. Highlights with silicon callouts:

- **Figure BotQ**: ~1 robot/hour cadence on Figure 03 line; >350 units built; onboard compute remains custom Figure stack (no public Jetson/Intel disclosure) ([Humanoid Guide](https://humanoid.guide/automate-2026-humanoid-robots/)).
- **Boston Dynamics electric Atlas**: First production fleet shipping; 2026 allocation reportedly sold out to Hyundai RMAC and Google DeepMind ([Humanoid Guide](https://humanoid.guide/automate-2026-humanoid-robots/)).
- **NVIDIA Humanoid Pavilion**: First-ever dedicated humanoid floor at Automate, 20+ platforms — XPENG IRON drew the largest Chinese crowd ([Automate / A3](https://www.automateshow.com/a3-press-releases/automate-2026-brings-popular-humanoid-robot-forum-and-nvidia-sponsored-humanoid-robot-pavilion-to-show)).
- **Mantis Robotics**: Dual-arm fenceless cobot built around its Physical AI stack — direct shot at Universal Robots / Doosan envelope ([RoboticsTomorrow](https://www.roboticstomorrow.com/news/2026/06/22/inorbitai-demonstrates-the-future-of-multi-vendor-robot-orchestration-and-physical-ai-at-automate-2026/26757/)).
- **Dexory Storage Health**: Next-gen autonomous inventory robot + analytics layer announced on the show floor ([Automate news roundup](https://www.therobotreport.com/)).
- **Innovation Awards (June 23)** picked AI-orchestration and Physical-AI integration entries as the dominant theme — a clean signal that the "robot is a sensor + a worker" framing has won ([Automate awards](https://www.automateshow.com/education-networking/automate-innovation-awards)).

## 3. Foundation models & software

Quiet week on net-new VLA releases — the field is digesting May's NVIDIA GR00T N1.7 + Isaac/Newton drop and Ant Group's LingBot-VLA earlier in 2026.

What's noteworthy this week:
- **GR00T deployments hit the show floor**: NVIDIA used Automate to anchor Pavilion partners on Isaac GR00T as the de-facto training pipeline — "NVIDIA's stack has quietly become the training layer beneath much of the field" ([Humanoid Guide](https://humanoid.guide/automate-2026-humanoid-robots/)).
- **ROS 2 Jazzy patch flow continues**; Lyrical Luth (2026.05) is moving from imminent to broadly adopted in tooling stacks. Operationally this matters because Jazzy + Nav2 + MoveIt 2 + a LeRobot-pulled VLA is now the textbook 2026 reference stack ([endoflife.date/ros-2](https://endoflife.date/ros-2), [youngju.dev stack overview](https://www.youngju.dev/blog/culture/2026-05-15-robotics-development-ros2-2026-nav2-moveit-isaac-sim-mujoco-lerobot-deep-dive.en)).

## 4. Customer deployments

The strongest section this week. The "named-customer / real shift" bar has clearly been crossed:

- **BMW × Figure** (June 26): Figure 03 enters Spartanburg, SC for logistics — sorting bulk components into sequencing trolleys for assembly delivery. Builds on the Figure 02 pilot that supported 30,000+ X3s and logged 1,250+ runtime hours, 90,000+ sheet metal parts at 5 mm precision ([TheAIInsider](https://theaiinsider.tech/2026/06/26/bmw-to-use-figure-ais-figure-03-for-logistics-work-at-us-factory/), [BMW Group](https://www.press.bmwgroup.com/global/article/detail/T0455864EN/bmw-group-to-deploy-humanoid-robots-in-production-in-germany-for-the-first-time?language=en)).
- **Toyota Ontario × Agility Digit**: Confirmed at Automate as live commercial shifts — 7+ Digit units active under a RaaS model, >100,000 cumulative warehouse cycles ([Humanoid Guide](https://humanoid.guide/automate-2026-humanoid-robots/)).
- **Hyundai RMAC & Google DeepMind × Boston Dynamics**: Initial 2026 electric Atlas fleet allocation now shipping ([Humanoid Guide](https://humanoid.guide/automate-2026-humanoid-robots/)).
- **Longcheer Technology × AGIBOT** (June 23–28): Six-day public livestream of multi-humanoid quality-inspection cells on a tablet production line in Nanchang. Format itself is the story — China is now broadcasting real-shift footage on YouTube/X to claim deployment leadership ([AGIBOT](https://www.agibot.com/article/231/detail/79.html)).

## 5. Competitive silicon watch

⚠️ **Intel-pressure read this week: high.** Two reinforcing signals:

1. **NVIDIA framed Automate**, not Intel. The Humanoid Pavilion sponsorship + Jetson Thor (Blackwell, 2,070 FP4 TFLOPS, 40–130 W) is now the de-facto reference compute for new humanoid programs, and the GR00T Reference design Unitree H2 Plus build keeps adding gravity to that stack ([NVIDIA newsroom](https://nvidianews.nvidia.com/news/nvidia-open-humanoid-robot-reference-design), [NVIDIA developer blog](https://developer.nvidia.com/blog/introducing-nvidia-jetson-thor-the-ultimate-platform-for-physical-ai/)).
2. **Intel's only fresh edge-robotics push** in market remains the Core Ultra Series 3 from Computex (June 2): 1.9× LLM, 2.3× perf/W/$ video analytics, 4.5× VLA throughput claims, 130+ design wins, RoBee demo at CES. Strong story on the spec sheet — but it's now ~four weeks old with no fresh momentum at Automate ([Intel Newsroom](https://newsroom.intel.com/artificial-intelligence/intel-core-ultra-series-3-for-edge-ai-robotics)).

Meanwhile **Qualcomm RB5/RB6** remained quiet at Automate; **Hailo** is leveraging the Hailo-10H automotive ramp (AEC-Q100 Grade 2) into adjacent edge-robotics deals; **Ambarella** continues to be M&A-discussed in light of humanoid demand patterns ([Optimus Delta substack](https://optimusdelta.substack.com/p/amba-gets-bought-and-humanoids-are)).

China silicon side: **Black Sesame × SIIC Tech Capital** (June 8) formalized an embodied-AI ecosystem alliance — a clear signal that domestic humanoid silicon is moving from pure auto-SoC plays into robotics ([Gasgoo](https://autonews.gasgoo.com/articles/news/gasgoo-daily-black-sesame-siic-tech-capital-to-advance-embodied-ai-robotics-ecosystem-2064339022514860033)).

## 6. China robotics ecosystem

- **AGIBOT** ran a public six-day livestream of humanoids at Longcheer's Nanchang tablet factory (June 23–28). This is the most aggressive operational-PR move from China to date — a direct counter to BMW/Figure narrative ([AGIBOT](https://www.agibot.com/article/231/detail/79.html)).
- **Unitree IPO** (cleared STAR Market review June 1) continues to underpin valuations across the China humanoid stack. NVIDIA's choice of Unitree H2 Plus as the GR00T Reference body remains the most consequential US-China robotics handshake this quarter ([Gasgoo](https://autonews.gasgoo.com/articles/icv/xiaozhi-weekly-news-byd-developing-humanoid-robots-unitree-passes-star-market-ipo-review-2063989705908273153)).
- **XPENG IRON** confirmed at Automate as one of the few non-US platforms drawing show-floor crowds; mass production end-2026, retail-store deployment Q1 2027 ([Humanoid Guide](https://humanoid.guide/automate-2026-humanoid-robots/)).
- **MIIT/SASAC 10,000-unit mandate** (June 9): local governments and SOEs must file plans by end of June, progress reports by November. The AGIBOT livestream is the first visible execution against that filing deadline ([Pandaily](https://pandaily.com/miit-sasac-humanoid-robot-real-scene-training-2026-jun2026)).

## 7. Policy / standards / safety

- **EU AI Act Digital Omnibus simplification** approved by the European Parliament on June 16, 2026 — relevant for robotics because it confirms the AI Act + revised Machinery Regulation dual-conformity model for AI-enabled machines, with transparency rules live in August 2026 ([Inside Global Tech](https://www.insideglobaltech.com/2026/05/28/eu-ai-act-update-timeline-relief-targeted-simplification-and-new-prohibitions/)).
- **Germany / VDMA pressure on Berlin** (June 26): automatica survey reveals 82% of German decision-makers want Beijing-style subsidies for humanoid robotics; 78% view AI/robotics deployment as essential for industrial competitiveness ([RoboticsTomorrow](https://www.roboticstomorrow.com/news/2026/06/26/german-economy-calls-for-faster-humanoid-robotics-adoption/26778/)).
- **Safety standards baseline**: ISO 10218-1/-2:2025 + ANSI/A3 R15.06-2025 are the operative rulebooks at Automate. ISO 25785-1 (humanoid-specific) remains Working Draft, publication 2026–2027 ([Theresa Robot blog](https://theresarobotforthat.com/blog/humanoid-robot-safety-standards-2026/)).
- Surgical robotics: Medtronic continues to expand Hugo 510(k) filings; no new FDA clearances confirmed inside the 7-day window ([MedTronic newsroom](https://news.medtronic.com/2026-06-03-Medtronic-submits-510-k-filings-to-expand-Hugo-TM-robotic-assisted-surgery-system-into-general-and-gynecologic-specialties-in-the-United-States)).

## 8. Conferences & signals

- **Automate 2026** (Chicago, June 22–25): 50,000+ attendees, 1,000+ exhibitors, 450,000 sq ft. The first Automate where the floor question shifted from "will humanoids work?" to "how fast can we absorb them?" ([Humanoid Guide](https://humanoid.guide/automate-2026-humanoid-robots/), [BusinessWire](https://www.businesswire.com/news/home/20260615964855/en/A3s-Automate-2026-Opens-Next-Week-in-Chicago)).
- **Innovation Awards** (June 23): Physical-AI-integration entries dominated — orchestration > individual product is now the framing investors and OEMs reward ([Automate](https://www.automateshow.com/education-networking/automate-innovation-awards)).
- **AGIBOT public livestream** (June 23–28): not a conference per se, but China is reframing public robotics events as 24/7 production-line streams. Worth tracking as a new genre.
- **Next on calendar**: ICRA 2026 closed June 5 (Vienna); Humanoids 2026, IROS, and ROSCon remain the autumn signals. No major silicon keynotes scheduled for July.

## So what — strategic implications

- **The "named customer" race has been won — by Figure, Agility, and (in China) AGIBOT/Unitree.** Anyone selling silicon, software, or services into humanoids should design their 2H26 plan around supporting these specific stacks. Lab-to-floor framing is over.
- **Intel-pressure: rising.** Core Ultra Series 3 hit Computex with strong claims, but Automate week made clear that NVIDIA owns the humanoid narrative end-to-end. The window for Intel to insert itself is shrinking from quarters to weeks; expect a forced response (a fresh edge-robotics reference design or a marquee humanoid design-win) before Hot Chips and Intel Innovation in Q3.
- **Agility's SPAC opens the comparable.** Once AGLT trades, every humanoid round (and every adjacent silicon pitch) will be priced off that tape. Watch for the implied per-robot revenue multiple — it will reshape investor patience.
- **China is now broadcasting deployment**, not just demos. AGIBOT's six-day livestream + Longcheer co-marketing is a template others will copy. Western OEMs need to weigh open-shop-floor PR against IP/safety risk.
- **What to watch next week**: (1) reactions to BMW's Spartanburg expansion — Mercedes/Ford follow-on signals; (2) any silicon-vendor counterpunch to NVIDIA's Automate dominance; (3) the late-June Chinese local-government filings under the MIIT mandate; (4) Apptronik/Mercedes operational updates.

## Worth a deeper read

**Agility Robotics × Churchill Capital ($2.5B SPAC).** This is the single most important capital-markets event for robotics in 2026 so far. Once "AGLT" trades, every private humanoid valuation gets a public anchor, and any softness in the after-market price will compress the next wave of Series C/D rounds. Equally important: the deal's $300M+ Digit v5 multi-year order book — the first concrete public-disclosure of humanoid revenue scale — gives silicon and software vendors a usable BOM/unit-economics datapoint to model their TAM ([source](https://theaiinsider.tech/2026/06/24/agility-robotics-to-go-public-through-2-5-billion-merger-with-spac-churchill-capital-corp-xi/)).

**BMW × Figure 03 at Spartanburg.** Don't read this as "another humanoid pilot." Read it as the first time a Tier-1 OEM publicly expanded humanoid scope from a single-cell pilot (body shop) into a logistics-floor sequencing job — i.e., variable-task, mixed-SKU work that historically required AMR + cobot + human. If Figure can hold uptime in that envelope, the next BMW step is multi-plant, and the precedent puts Mercedes/Hyundai/Toyota on a forced clock ([source](https://theaiinsider.tech/2026/06/26/bmw-to-use-figure-ais-figure-03-for-logistics-work-at-us-factory/)).

**Germany's VDMA call for subsidies.** Easy to dismiss as lobbying, but this is the first time a top-tier industrial-policy voice in the EU has explicitly framed humanoid robotics as a China-vs-West subsidy race. If Berlin responds (even modestly) before automatica 2027, expect a corresponding EU-level instrument — and silicon/component sourcing rules will follow ([source](https://www.roboticstomorrow.com/news/2026/06/26/german-economy-calls-for-faster-humanoid-robotics-adoption/26778/)).
