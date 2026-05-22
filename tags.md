---
layout: page
title: Topics
permalink: /tags/
---

Browse all briefs grouped by topic.

{% if site.tags.size == 0 %}
*Tags will appear here as briefs are tagged.*
{% else %}

<p>
{% assign sorted_tags = site.tags | sort %}
{% for tag in sorted_tags %}
<a href="#{{ tag[0] | slugify }}" style="display:inline-block; padding:4px 10px; margin:3px; background:#f0f0f0; border-radius:12px; text-decoration:none; font-size:0.9em;">{{ tag[0] }} <span style="color:#888;">({{ tag[1] | size }})</span></a>
{% endfor %}
</p>

{% for tag in sorted_tags %}
<h2 id="{{ tag[0] | slugify }}" style="margin-top:2em; padding-top:0.5em; border-top:1px solid #eee;">{{ tag[0] }}</h2>
<ul>
{% for post in tag[1] %}
<li><strong>{{ post.date | date: "%b %-d, %Y" }}</strong> — <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
{% endfor %}

{% endif %}
