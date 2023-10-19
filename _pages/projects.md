---
permalink: /projects/
title: "Projects"
author_profile: true
---

{% if author.github %}
  You can find most of my projects on <u><a href="{{author.github}}">my GitHub profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
Not updated yet, might be filled out soon.
