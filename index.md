---
layout: archive
permalink: /
title: ""
---

<div style="text-align:center"><img src="/images/coverpic.jpg" width="90%"></div>

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
