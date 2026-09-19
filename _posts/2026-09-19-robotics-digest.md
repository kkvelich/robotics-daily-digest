---
layout: post
title: "Robotics Brief — 2026-09-19"
date: 2026-09-19
tags: [funding, products, humanoids, foundation-models, conferences]
---

# Robotics Market Sensing — 2026-09-19

## TL;DR
- **SoftBank acquires Marc Raibert's Robotics & AI Institute (RAI) from Hyundai** — terms undisclosed, CFIUS review underway; SoftBank re-enters robotics R&D just months after selling its Boston Dynamics stake back to Hyundai.
- **Skild AI crosses $100M ARR** — robot foundation model hit the milestone 10 months after first commercial deployment; 60+ customers; built on NVIDIA AI infrastructure.
- **Faraday Future launches 9-robot lineup today (FF 919 event, 5 PM PDT)** — humanoid, quadruped, and mobile manipulator form factors; compute not yet disclosed; IMTS 2026 closes today as the backdrop.

---

## 1. Funding & M&A

| Company | Stage | Amount | Lead investor | What they build | Compute platform | Source |
|---|---|---|---|---|---|---|
| Robotics & AI Institute (RAI) | Acquisition by SoftBank Group | Undisclosed | SoftBank Group Corp. | Robotics research: manipulation, perception, navigation, physical AI | N/A | [The Robot Report](https://www.therobotreport.com/softbank-agrees-to-acquire-robotics-and-ai-institute/) (date via search index) |

**RAI context:** Cambridge, MA lab founded by Marc Raibert; spun out of Hyundai's 2022 Boston Dynamics acquisition. SoftBank previously owned Boston Dynamics 2017–2021, then sold its stake to Hyundai in a $325M transaction finalized July 2026. The RAI deal is now being reviewed by CFIUS. Financial terms not yet public.

---

## 2. Product Launches & Demos

- **Faraday Future FF 919 launch event (today, 5 PM PDT)** — FFAI is unveiling 9 new AI-powered robot devices: humanoid, quadruped, and mobile manipulator form factors across large, medium, and small sizes; 4 industry solutions across education, research, security, and inspection. Also launching the "All-New Futurist" for sale. Compute: **not disclosed**. FF is simultaneously at IMTS 2026 (Chicago, closes today) demoing its Aegis quadruped security series. Note: FFAI is a financially distressed EV-turned-robotics company — treat this as strategic positioning to watch, not validated deployment scale. [BusinessWire pre-announcement](https://www.businesswire.com/news/home/20260916196720/en/Faraday-Future-to-Unveil-Nine-New-AI-Powered-Robots-and-Four-Industry-Solutions-at-Its-Annual-919-Launch-Event-Completing-Its-One-Brain-Multi-Form-Multi-Capability-Robot-World-2.0)

---

## 3. Foundation Models & Software

- **Skild AI hits $100M annual recurring revenue** — 10 months after first commercial deployment of its S1 robot foundation model; 60+ customers across logistics, warehousing, manufacturing, security, and food prep. S1 achieves 66% success rate on previously unseen manipulation tasks (vs. 9% for language-prompted baselines), with in-context generalization on tasks up to 10 minutes. Built entirely on **NVIDIA AI infrastructure**. [Robotics & Automation News](https://roboticsandautomationnews.com/2026/09/18/skild-ai-reaches-100-million-in-annual-recurring-revenue-after-10-months/104958/) (date via URL: /2026/09/18/) / [NVIDIA + Skild collaboration](https://www.unite.ai/nvidia-details-skild-ai-collaboration-behind-s1-robot-foundation-model/)

---

## 4. Customer Deployments

*Nothing material today.* (Tesla Optimus Ningbo audit and Locus Robotics/Kimball Midwest were covered in the Sep 18 brief.)

---

## 5. Competitive Silicon Watch ⚠️

*No new silicon announcements in today's 24h window.* NVIDIA Jetson Orin Nano 2 (78 TOPS, 15W, H1'27 availability) was covered in the Sep 18 brief.

**Intel pressure note:** IMTS 2026 closes today with no Intel or AMD edge-robotics silicon keynote. Skild AI's S1 ecosystem running exclusively on NVIDIA infra deepens NVIDIA's developer lock-in in the foundation-model-for-robotics layer. Intel has no equivalent robotics-native inference runtime at this tier.

---

## 6. China Robotics Ecosystem

*Nothing material today.* (D-Robotics $400M Series C, Tesla Optimus Ningbo audit, Spirit AI, and UBTECH Liuzhou factory were covered in the Sep 18 brief.)

---

## 7. Policy / Standards / Safety

*Nothing material today.*

(Neptune Medical Triton 1 robotic endoscopy system received FDA 510(k) clearance — announced Sep 16, outside the 24h window.)

---

## 8. Conferences & Signals

- **IMTS 2026 — final day, Chicago (Sep 19).** The six-day show at McCormick Place closes today. This week's headline robotics announcement was **Universal Robots Gen 7** (CB7 Core controller, +40% compute, −30% footprint; 3 new arm models; PolyScope X software) — launched Sep 14 on day one. **No major new-silicon announcements emerged in the show's final days.** Intel, AMD, and Qualcomm were absent from robotics-compute keynotes. [IMTS](https://www.imts.com/index.cfm)

- **IROS 2026 — Pittsburgh, PA; opens September 27.** One week away; watch for manipulation, navigation, and VLA paper previews. No pre-conference announcements yet.

---

## So What — Strategic Implications

1. **SoftBank/RAI is a long bet on robot-learning research independence.** With Raibert's lab in hand, SoftBank could incubate an alternative to NVIDIA Isaac or Google GR00T for the physical-AI training stack. Short-term: no product impact. Long-term: watch for SoftBank-funded robotics compute or model plays that fragment the current NVIDIA-centric ecosystem.

2. **Skild AI at $100M ARR on NVIDIA infra is the clearest proof yet that the "foundation model + edge compute" two-layer stack is real and scaling.** Intel's OpenVINO and Core Ultra NPU have no equivalent plug-in story for the manipulation-model layer. This is the most actionable competitive gap for Intel's hybrid-edge robotics narrative.

3. **Faraday Future's 9-robot lineup is a wildcard to monitor, not act on.** FFAI's financial distress makes execution risk high, but if any compute supplier surfaces today (NVIDIA, Qualcomm, or a China stack), it's a market signal worth filing. Check the livestream at robotics.ff.com.

4. **IMTS closing without Intel or AMD edge-robotics presence is a signal in itself.** At the largest North American manufacturing show, the vacuum was filled entirely by NVIDIA (Jetson Orin Nano 2, Isaac), Universal Robots (physical AI–ready CB7 controller), and Chinese cobots. Intel's edge-robotics narrative needs a flagship presence at IROS (Sep 27) or NVIDIA GTC (next cycle) to stay in the conversation.
