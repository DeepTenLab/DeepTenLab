---
---

# DeepTenLab

A brief description of the Lab ... TODO

{%
  include figure.html
  image="images/home/group-photo-team.jpg"
  width="100%"
%}

{% include section.html %}

## Highlights

{% capture text %}

A brief description of our research ... TODO

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/home/highlight-research.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

A brief description of our projects ... TODO

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/home/highlight-project.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

A brief description of our team ... TODO

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/home/highlight-team.jpg"
  link="team"
  title="Our Team"
  text=text
%}
