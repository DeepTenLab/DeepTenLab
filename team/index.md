---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

A brief description of our team ... TODO

{%
  include figure.html
  image="images/home/group-photo-team.jpg"
  width="100%"
%}


{% include section.html %}

Our PI ... A brief description of the main people working in the lab ... TODO

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
<!-- 
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %} 
-->

{% include section.html %}

Our PHD Students ... A brief description of the PHD students working in the lab ... TODO

{% include list.html data="members" component="portrait" filter="role == 'phd'" %}

{% include section.html %}

Our Graduate Students ... A brief description of the Graduate students working in the lab ... TODO

{% include list.html data="members" component="portrait" filter="role == 'graduate'" %}

{% include section.html %}

Our Alumni Students ... A brief description of the Alumni students who had worked in the lab ... TODO

{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}

<!-- {% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %} -->
