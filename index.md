---
layout: archive
permalink: /
image:
  feature: wood-texture-1600x800.jpg
---

<div class="titles">
{% for post in site.categories.media limit:8 %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.titles -->
</div>
