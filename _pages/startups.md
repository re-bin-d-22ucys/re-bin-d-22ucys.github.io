---
layout: archive
title: "Startups and Initiatives"
permalink: /startups/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.startups reversed %}
  {% include archive-single.html %}
{% endfor %}
