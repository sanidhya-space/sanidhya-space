---
layout: archive
title: "Projects"
permalink: /projects/
image:
  feature:
  teaser:
  thumb:
---

<div class="tiles">
{% for post in site.categories.projects %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
