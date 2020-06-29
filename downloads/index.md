---
layout: default
title: Downloads
permalink: /downloads/
order: 3
---

# Downloading Anima

<p align="justify">Anima and Anima scripts are open-source and thus available on github. More information on how to get them and compile / configure them is available from the documentation.</p>

<ul>
{% for repository in site.github.public_repositories %}
{% if repository.name == "Anima-Public" %}
<li>Anima <a href="{{ repository.html_url }}">Github repository</a></li>
{% endif %}
{% if repository.name == "Anima-Scripts-Public" %}
<li>Anima scripts <a href="{{ repository.html_url }}">Github repository</a></li>
{% endif %}
{% if repository.name == "Anima-Scripts-Data-Public" %}
<li>Anima scripts data <a href="{{ repository.html_url }}">Github repository</a></li>
{% endif %}
{% endfor %}
</ul>

<p align="justify">
Anima and Anima scripts also come in several binary packages released from time to time.
</p>

{% assign release = site.github.latest_release %}
<p align="justify">
<strong>Latest Anima binary release</strong>: {{ release.name }} - <a href="{{ release.html_url }}">Release notes</a>
</p>
<ul>
{% for asset in release.assets %}
<li>
<a href="{{ asset.browser_download_url }}">{{ asset.name }}</a>
</li>
{% endfor %}
</ul>

<p align="justify">
<strong>Latest Anima scripts release</strong>: Anima scripts v2.2 - <a href="https://github.com/Inria-Visages/Anima-Scripts-Public/releases/tag/v2.2">Release notes</a>
</p>
<ul>
<li>
<a href="https://github.com/Inria-Visages/Anima-Scripts-Public/archive/v2.2.zip">Zip file</a>
</li>
</ul>

<p align="justify">
<strong>Latest Anima scripts data release</strong>: Anima scripts data v2.1 - <a href="https://github.com/Inria-Visages/Anima-Scripts-Data-Public/releases/tag/v2.1">Release notes</a>
</p>
<ul>
<li>
<a href="https://github.com/Inria-Visages/Anima-Scripts-Data-Public/archive/v2.1.zip">Zip file</a>
</li>
</ul>

