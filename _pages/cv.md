---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
file_url: "files/TRamaraj_CV_Sep2020.pdf"
file_type: "application/pdf"
last_update: "September 2020"

---
{% include base_path %}

{% assign rel_url=page.file_url | absolute_url %}
{% include file.html url=rel_url media_type=page.file_type update_date=page.last_update %}
