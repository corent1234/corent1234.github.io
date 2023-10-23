---
layout: archive
permalink: /projects/
title: "Projects"
author_profile: true
---

{% if author.github %}
     You can find most of my projects on <u><a href="https://github.com/{{ author.github }}"><i class="fab fa-fw fa-github" aria-hidden="true"></i>my GitHub profile</a></u>
{% endif %}

This section is not completed yet, I might update it soon with more interesting projects.

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}



