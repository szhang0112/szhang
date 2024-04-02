---
title: "Sai Zhang - Publications"
layout: gridlay
excerpt: "Publications"
sitemap: false
permalink: /publications/
---

<script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

See also [Google Scholar](https://scholar.google.com/citations?user=cnFBCDEAAAAJ); * for equal contribution, &#10013;&#xFE0E; for correspondence, group members highlighted in bold.

### Manuscripts &#38; Preprints
<ul>
{% for publi in site.data.preprint %}
<li>{{ publi.title }}<br>
  {{ publi.authors }}<br>
  {{ publi.display }}
</li>
{% endfor %}
</ul>

### Peer-Reviewed Papers
<ul>
{% for publi in site.data.publist %}
<li>{{ publi.title }}<br>
  {{ publi.authors }}<br>
  {{ publi.display }}
</li>
{% endfor %}
</ul>

### Patents
<ul>
{% for publi in site.data.patent %}
<li>{{ publi.title }}<br>
  {{ publi.authors }}<br>
  {{ publi.display }}
</li>
{% endfor %}
</ul>
