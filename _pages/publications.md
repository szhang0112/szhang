---
title: "Sai Zhang - Papers"
layout: gridlay
excerpt: "Papers"
sitemap: false
permalink: /publications/
---

<script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

# Papers

(See also [Google Scholar](https://scholar.google.com/citations?user=cnFBCDEAAAAJ); <sup>&#9733;</sup> for equal contribution)

## Manuscripts <sup>&#38;</sup> Preprints
<ul>
{% for publi in site.data.preprint %}
<li>{{ publi.title }}<br>
  {{ publi.authors }}<br>
  {{ publi.display }} [<a href="{{ publi.url }}">Link</a>]
</li>
{% endfor %}
</ul>

## Peer-reviewed Papers
<ul>
{% for publi in site.data.publist %}
<li>{{ publi.title }}<br>
  {{ publi.authors }}<br>
  {{ publi.display }} [<a href="{{ publi.url }}">Link</a>]
</li>
{% endfor %}
</ul>
