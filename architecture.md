---
layout: page
title: Architecture
permalink: /architecture/
---

{% for arch in site.architecture %}
  - [{{ arch.title }}]({{ arch.url }})
{% endfor %}