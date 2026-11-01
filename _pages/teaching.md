---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

## Courses Taught

{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## Guest Lectures

{% for post in site.guest_lectures reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}