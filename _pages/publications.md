---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find my papers on [my Google Scholar profile](https://scholar.google.com/citations?user=5bowhjcAAAAJ&hl=zh-CN&oi=ao) 


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
