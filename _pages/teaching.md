---
title: "Sai Zhang - Teaching"
layout: gridlay
excerpt: "Teaching"
sitemap: false
permalink: /teaching/
---

<script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

## Teaching Assistant
<ul>
{% for ta in site.data.ta %}
<li>{{ ta.course }}
  {{ ta.univ }}
  {{ ta.time }}
</li>
{% endfor %}
</ul>
