---
title: "Sai Zhang - Publications"
layout: gridlay
excerpt: "Publications"
sitemap: false
permalink: /publications/
---

<script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

# Publications

(See also [Google Scholar](https://scholar.google.com/citations?user=cnFBCDEAAAAJ); <sup>&#9733;</sup> for equal contribution)

<ul>
{% for publi in site.data.publist %}
<li>{{ publi.title }}
  {{ publi.authors }}
  {{ publi.display }} [<a href="{{ publi.url }}">Link</a>]
</li>
{% endfor %}
</ul>
