---
layout: page
permalink: /publications/index.html
title: Publications
description: Publications by Peizhou Huang on multimodal agents, reasoning, and computer vision.
---

## First-Author & Lead Work

{% for paper in site.data.publications %}
{% if paper.group == 'lead' %}
{% include publication.html paper=paper %}
{% endif %}
{% endfor %}

## Collaborations

{% for paper in site.data.publications %}
{% if paper.group == 'collaboration' %}
{% include publication.html paper=paper %}
{% endif %}
{% endfor %}
