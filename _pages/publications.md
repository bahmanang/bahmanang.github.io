---
layout: archive
title: 
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in site.publication reversed %}
  {% include archive-single.html %}
{% endfor %}
