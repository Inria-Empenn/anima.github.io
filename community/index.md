---
layout: default
title: Community
permalink: /community/
order: 4
---

# Anima contributors

<p align="justify">
We thank the contributors over the years for their valuable corrections and updates to the software. You can yourself join the crowd by getting involved on the Anima Github repositories available from the <a href="{{ site.baseurl }}/downloads">downloads page</a>.
</p>

{% for contributor in site.github.contributors %}
[![Avatar]({{ contributor.avatar_url }}){: style="width: 64px;"}]({{ contributor.html_url }}) [{{ contributor.login }}]({{ contributor.html_url }})
{% endfor %}

# Becoming a contributor ?

Anima and anima scripts are on open licenses. There are several ways to contribute to them. You can either:

* provide feedback on an issue on the issue pages of [Anima](https://github.com/Inria-Visages/Anima-Public/issues) or [Anima scripts](https://github.com/Inria-Visages/Anima-Scripts-Public/issues)
* propose a pull-request to correct a bug or provide new features. For this, fork one of the repositories in the github interface, create your branch and send us a pull-request when ready. 

More details on theses two options are available on the [Github documentation](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/creating-an-issue-or-pull-request).
