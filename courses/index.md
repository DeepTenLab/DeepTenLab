---
title: Courses
nav:
  order: 7
  tooltip: Active courses and workshops
---

# {% include icon.html icon="fa-solid fa-graduation-cap" %}Courses

{% assign active_courses = site.data.courses | where: "active", true %}

{% if active_courses.size > 0 %}

{% for course in active_courses %}

{% capture course_link %}courses/{{ course.slug }}{% endcapture %}

{%
  include card.html
  title=course.title
  subtitle=course.subtitle
  description=course.description
  image=course.poster
  link=course_link
  style="large"
%}

{% endfor %}

{% else %}

No active courses at this time. Check back soon!

{% endif %}
