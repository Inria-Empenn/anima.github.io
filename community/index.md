---
layout: default
title: Community
permalink: community/
order: 4
---

Anima, both main code and scripts, would not have been developed without the constant support of our institutions. Thanks to all of them !

* [CNRS](https://www.cnrs.fr) and particularly the [IRISA](https://www.irisa.fr)
* [Inria](https://www.inria.fr) and particularly [Inria Rennes](https://www.inria.fr/rennes)
* [Inserm](https://www.inserm.fr)
* [University of Rennes 1](https://www.univ-rennes1.fr)

![logos]({{ site.base-url }}images/logos_equipe.png)

# Anima contributors

<p align="justify">
We thank the contributors over the years for their valuable corrections and updates to the software. You can yourself join the crowd by getting involved on the Anima Github repositories available from the <a href="{{ site.base-url }}downloads/">downloads page</a>.
</p>

{% for contributor in site.data.contributors %}
[![Avatar]({{ contributor.avatar_url }}){: style="width: 64px;"}]({{ contributor.html_url }}) [{{ contributor.login }}]({{ contributor.html_url }})
{% endfor %}

# Anima scripts contributors

<p align="justify">
We also thank the contributors over the years for their valuable corrections and updates to the scripts built on Anima. You can yourself join the crowd by getting involved on the Anima Github repositories available from the <a href="{{ site.base-url }}downloads/">downloads page</a>.
</p>

{% for contributor in site.data.contributors_scripts %}
[![Avatar]({{ contributor.avatar_url }}){: style="width: 64px;"}]({{ contributor.html_url }}) [{{ contributor.login }}]({{ contributor.html_url }})
{% endfor %}

# Want to become a contributor?

Anima and anima scripts are on open licenses. There are several ways to contribute to them. You can either:

* provide feedback on an issue or a feature request on the issue pages of [Anima](https://github.com/Inria-Visages/Anima-Public/issues) or [Anima scripts](https://github.com/Inria-Empenn/Anima-Scripts-Public/issues)
* propose a pull-request to correct a bug or provide new features. For this, fork one of the repositories in the github interface, create your branch and send us a pull-request when ready. 

More details on theses two options are available on the [Github documentation](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/creating-an-issue-or-pull-request).
