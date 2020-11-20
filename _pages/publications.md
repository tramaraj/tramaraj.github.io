---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### [GOOGLE SCHOLAR](https://scholar.google.com/citations?hl=en&user=5a9X7N0AAAAJ&view_op=list_works&sortby=pubdate)

### [NCBI PUBMED BIBLIOGRAPHY](https://www.ncbi.nlm.nih.gov/myncbi/thiruvarangan.ramaraj.1/bibliography/public/)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
