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
{% for publi in site.data.recentpub %}
<li>{{ publi.authors }} ({{ publi.year }}) {{ publi.title }}. <a href="{{ publi.url }}">{{ publi.display }}</a>.
[PMID: <a href="https://www.ncbi.nlm.nih.gov/pubmed/{{ publi.pmid }}">{{ publi.pmid }}</a>]
[<a href="https://badge.dimensions.ai/details/pmid/{{ publi.pmid }}">Citations</a>]
</li>
{% endfor %}
</ul>
