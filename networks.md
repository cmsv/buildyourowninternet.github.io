---
title: Community Networks
layout: default
---

A list of <span class='forming'>forming</span>, <span class='active'>active</span> or <span class='inactive'>inactive</span> community-run networks. Want to add a network? [Edit the list](https://github.com/buildyourowninternet/buildyourowninternet.github.io/edit/master/_data/networks.csv) or tweet info using #buildyourowninternet. 

From [networks.csv](https://github.com/buildyourowninternet/buildyourowninternet.github.io/blob/master/_data/networks.csv):

<ul>
{% for network in site.data.networks %}
  <li class="{{ network.status }}"><a href="{{ network.url }}" target="_blank">{{ network.name }}</a> @ <a href="{{ network.localeId }}" target="_blank">{{ network.locale }}</a></li>
{% endfor %}
</ul>

Information about community networks was gathered from various sources including https://en.wikipedia.org/wiki/List_of_wireless_community_networks_by_region , https://www.metamesh.org/community-wifi-resources and https://sudoroom.org/wiki/Mesh/Other_mesh_projects .
