---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
[I'm an inline-style link](https://https://scholar.google.com.hk/citations?hl=en&user=zlCBoJIAAAAJ&view_op=list_works&sortby=pubdate)
Please check the Google Scholar for publications <u><a href="{https://scholar.google.com.hk/citations?hl=en&user=zlCBoJIAAAAJ&view_op=list_works&sortby=pubdate}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
