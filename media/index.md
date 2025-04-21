---
title: Media
nav:
  order: 4
  tooltip: Media, tutorials, online courses
---

# {% include icon.html icon="fa-brands fa-youtube" %}Media

A short discription about our media

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
