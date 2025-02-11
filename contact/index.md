---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Department of computer science, Tarbiat modares university-Tehran-Iran

{%
  include button.html
  type="email"
  text="rezghi@modares.ac.ir"
  link="rezghi@modares.ac.ir"
%}
{%
  include button.html
  type="phone"
  text="021 828 8448 0"
  link="+982182884480"
%}
{%
  include button.html
  type="phone"
  text="021 828 8508 2"
  link="+982182885082"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/twwN65BxY76qkZU19"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/loc1.png"
  caption="University"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/loc2.png"
  caption="Our Department"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Col1
Col1
Col1
{% endcapture %}

{% capture col2 %}
Col2  
Col2
Col2
{% endcapture %}

{% capture col3 %}
Col3
Col3
Col3
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
