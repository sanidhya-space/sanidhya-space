---
layout: archive
title: "Blogs"
permalink: /blogs/
image:
  feature:
  teaser:
  thumb:
ads: false  
---

<div class="tiles">
<h2> Life </h2>
{% for post in site.categories.blogs-life %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
<p>sanidhyaM<br>here</p>
<div class="tiles">
<h2> Space </h2>
{% for post in site.categories.blogs-space %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->