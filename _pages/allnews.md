---
title: "News"
layout: textlay
excerpt: "Sai Zhang at Stanford University."
sitemap: false
permalink: /allnews.html
---

## News

{% for article in site.data.news %}
{{ article.date }}
<ul>
<em>{{ article.headline | markdownify}}</em>
</ul>
{% endfor %}
