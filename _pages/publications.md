---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

My work covers AI and intelligent data analytics for energy and engineering systems, including renewable-energy forecasting, microgrid optimization, uncertainty-aware structural monitoring, catalytic hydrogen microreactors, industrial fault diagnosis, and deployable edge intelligence. Role information is provided in each entry where applicable.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
