---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Research Projects

<ul>
{% for post in site.portfolio reversed %}
  {% if post.category == "research" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
</ul>

## Outreach

<ul>
{% for post in site.portfolio reversed %}
  {% if post.category == "outreach" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
</ul>

## Educational Resources

<ul>
{% for post in site.portfolio reversed %}
  {% if post.category == "education" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
</ul>