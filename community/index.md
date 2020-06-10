---
layout: default
title: Community
permalink: /community/
order: 2
---

# Anima contributors

{% for contributor in site.github.contributors %}
[![Avatar]({{ contributor.avatar_url }}){: style="width: 64px;"}]({{ contributor.html_url }}) [{{ contributor.login }}]({{ contributor.html_url }})
{% endfor %}
