---
title: Community Networks
layout: default
---

A non-normative list of <span class='forming'>forming</span>, <span class='active'>active</span> or <span class='inactive'>inactive</span> community-run networks. Want to add a network? [Edit the list](https://github.com/buildyourowninternet/buildyourowninternet.github.io/edit/master/_data/networks.csv) or tweet info using #buildyourowninternet. 

From [networks.csv](https://github.com/buildyourowninternet/buildyourowninternet.github.io/blob/master/_data/networks.csv):

<ul>
{% for network in site.data.networks %}
  <li class="{{ network.status }}"><a href="{{ network.url }}" target="_blank">{{ network.name }}</a> @ <a href="{{ network.localeId }}" target="_blank">{{ network.locale }}</a></li>
{% endfor %}
</ul>
