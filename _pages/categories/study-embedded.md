---
layout: archive
permalink: /categories/system-embedded/
types: posts
---

{% assign posts = site.categories['system-embedded']%}
{% for post in posts %}
  {% include archive-single-informative.html type=page.entries_layout %}
{% endfor %}

