---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% if author.github %}
  You can find most of my projects in <u><a href="{{author.googlescholar}}"> my GitHub</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
