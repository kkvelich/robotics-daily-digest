---
layout: default
title: Home
---

# Daily Robotics Market Sensing

Edge AI for robotics — covering humanoids, AMRs, cobots, silicon (Intel / NVIDIA / Qualcomm / China), foundation models for robotics, customer deployments, policy, and the China ecosystem. Generated daily by a Claude Code remote agent.

## Latest digests

<ul style="line-height: 1.8;">
  {% for post in site.posts %}
    <li>
      <strong>{{ post.date | date: "%Y-%m-%d" }}</strong> &mdash;
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

---

*Next sweep: tomorrow morning, Phoenix time.*
