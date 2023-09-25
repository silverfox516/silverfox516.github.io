---
layout: archive
permalink: /categories/system-dp/
types: posts
---

{% assign posts = site.categories['system-dp']%}
{% for post in posts %}
  {% include archive-single-informative.html type=page.entries_layout %}
{% endfor %}

