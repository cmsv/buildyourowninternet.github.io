---
title: Community Networks
layout: default
---

A non-normative list of existing community-run internet. Want to add a network? [Edit the list](https://github.com/buildyourowninternet/buildyourowninternet.github.io/edit/master/_data/networks.csv) or tweet info using #buildyourowninternet. 

From [networks.csv](https://github.com/buildyourowninternet/buildyourowninternet.github.io/blob/master/_data/networks.csv):

<ul>
{% for network in site.data.networks %}
  <li><a href="{{ network.url }}" target="_blank">{{ network.name }}</a> ({{ network.status }}) @ <a href="{{ network.localeId }}" target="_blank">{{ network.locale }}</a></li>
{% endfor %}
</ul>
