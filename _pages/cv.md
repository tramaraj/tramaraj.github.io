---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
file url: "files/TRamaraj_CV_Sep2020.pdf"
file type: "application/pdf"
last_update: "September 2020"

---

My CV is available for download [here](https://tramaraj.github.io/files/TRamaraj_CV_Sep2020.pdf). Last updated Sep 2020.


{% include base_path %}

{% assign rel_url=page.file_url | absolute_url %}
{% include {{page.file_include }} url=rel_url media_type=page.file_type update_date=page.last_update_date %}

