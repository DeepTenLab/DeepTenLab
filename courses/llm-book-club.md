---
layout: default
---

{% assign course = site.data.courses | where: "slug", "llm-book-club" | first %}

# {% include icon.html icon="fa-solid fa-graduation-cap" %}{{ course.title }}

**{{ course.subtitle }}**

{% include section.html %}

{%
  include figure.html
  image=course.poster
  caption=course.title
  width="100%"
%}

{% include section.html %}

## About This Course

{{ course.description }}

{% include section.html %}

{%
  include button.html
  link=course.registration_url
  text="Register Now"
  icon="fa-solid fa-user-plus"
  tooltip="Sign up for this course"
%}
