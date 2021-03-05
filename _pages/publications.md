---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Please check the [Google Scholar](https://scholar.google.com.hk/citations?hl=en&user=zlCBoJIAAAAJ&view_op=list_works&sortby=pubdate) for my publications.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
