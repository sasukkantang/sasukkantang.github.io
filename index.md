---
layout: archive
permalink: /
title: "Latest Posts"
---

<div class="titles">
{% for post in site.categories.media limit:8 %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.titles -->
</div>