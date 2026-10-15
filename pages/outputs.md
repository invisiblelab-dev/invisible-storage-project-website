---
title: Outputs
description:
background: /assets/img/blueheader.png
permalink: /outputs/
---

<ul class="list-unstyled">
{% for pub in site.data.publications %}
  <li class="mb-3">
    {{ pub.authors }} <strong>{{ pub.title }}</strong>.
    <em>{{ pub.venue }}</em>, {{ pub.year }}.
    {% if pub.in_proceedings == false %}<span class="badge bg-secondary">Not in proceedings</span>{% endif %}
    <br>
    <a href="{{ pub.url }}">{% if pub.doi %}DOI: {{ pub.doi }}{% else %}PDF{% endif %}</a>
    {% if pub.arxiv %} · <a href="{{ pub.arxiv }}">arXiv</a>{% endif %}
  </li>
{% endfor %}
</ul>

%The research outputs from BCD.S+M will be disseminated through top scientific venues and released as an open-source prototype.  The project will include %software developers, senior researchers and students who are working on PhD and MSc thesis focused on the scope of the project.

%This page will be updated during the project duration.
