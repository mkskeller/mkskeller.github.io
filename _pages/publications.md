---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This is a selection of recent publications. You can find a complete list on <u><a href="https://scholar.google.co.uk/citations?user=mrpscToAAAAJ&hl=en">Google Scholar</a></u> and <u><a href="https://www.semanticscholar.org/author/Marcel-Keller/47315517">Semantic Scholar</a></u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
