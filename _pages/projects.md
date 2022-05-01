---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<h1 align="center">Coming Soon!</h1>

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
