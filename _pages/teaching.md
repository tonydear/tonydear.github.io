---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

This is a list of courses that I most recently taught. Descriptions and lists of topics are shown for the most updated offering of each course.

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
