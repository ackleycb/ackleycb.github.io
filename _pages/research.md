---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

### Anchor Tag (aka. Link)

This is an example of a [link](http://github.com "Github").

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
