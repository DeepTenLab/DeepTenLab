---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

At DeepTenLab, our team is composed of a diverse group of talented researchers and studentys who are passionate about advancing the field of AI. With expertise spanning mathematics, computer science, neuroscience, and engineering, our interdisciplinary team brings a wealth of knowledge and creativity to every project. We foster a collaborative and inclusive environment where ideas can flourish, and each member is encouraged to explore new avenues of research. Together, we are dedicated to pushing the frontiers of AI, developing novel algorithms, and applying them to solve real-world challenges. Our team's commitment to excellence is reflected in the high-impact publications we produce and the innovative projects we pursue across various domains.

{%
  include figure.html
  image="images/home/group-photo-team.jpg"
  width="100%"
%}


{% include section.html %}



{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html %}

Alumni members

{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}
