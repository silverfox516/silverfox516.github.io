---
layout: archive
permalink: /categories/devlog-mmistakes/
types: posts
---

{% assign posts = site.categories['devlog-mmistakes']%}
{% for post in posts %}
  {% include archive-single-informative.html type=page.entries_layout %}
{% endfor %}
