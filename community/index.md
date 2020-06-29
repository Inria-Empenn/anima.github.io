---
layout: default
title: Community
permalink: /community/
order: 4
---

# Anima contributors

<p align="justify">
We thank the contributors over the years for their valuable corrections and updates to the software. You can yourself join the crowd by getting involved on the Anima Github repositories available from the <a href="{{ site.baseurl }}downloads">downloads page</a>.
</p>

{% for contributor in site.github.contributors %}
[![Avatar]({{ contributor.avatar_url }}){: style="width: 64px;"}]({{ contributor.html_url }}) [{{ contributor.login }}]({{ contributor.html_url }})
{% endfor %}
