---
layout: default
permalink: /courses/llm-book-club/
---

{% assign c = site.data.courses | where: "slug", "llm-book-club" | first %}

{%
  include figure.html
  image=c.poster
  caption=c.title_fa
  width="100%"
%}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-graduation-cap" %} {{ c.title_fa }}

**{{ c.target_audience }} · {{ c.format }}**

{%
  include button.html
  link=c.registration_url
  text="ثبت‌نام در دوره"
  icon="fa-solid fa-user-plus"
  tooltip="Register for this course"
  style="filled"
%}

{% include section.html %}

{% capture col1 %}

## 📖 چشم‌انداز دوره

{{ c.vision }}

{% endcapture %}

{% capture col2 %}

## 📖 Course Vision

{{ c.vision_en }}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html %}

## 📘 {{ c.book_title }}

**{{ c.book_authors }}**

{% capture col1 %}

### سرفصل‌های اصلی

{% for ch in c.chapters %}
- {{ ch }}
{% endfor %}

{% endcapture %}

{% capture col2 %}

### Key Topics

{% for ch in c.chapters_en %}
- {{ ch }}
{% endfor %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% capture text %}

این مباحث در ۵ هفته، با تلفیق تئوری، بحث گروهی و کدنویسی زنده پوشش داده خواهد شد.

These topics will be covered over 5 weeks, combining theory, group discussion, and live coding.

{% endcapture %}

{%
  include feature.html
  image="https://cdn-icons-png.flaticon.com/512/2232/2232667.png"
  title="ساختار جلسات | Session Format"
  text=text
%}

{% include section.html %}

{% capture text %}

{{ c.session_format }}

{{ c.session_format_en }}

{% endcapture %}

{{ text | markdownify }}

{% include section.html %}

## 📅 زمان و مکان | Schedule & Location

| | فارسی | English |
|---|---|---|
| 📅 **تاریخ شروع** | {{ c.start_date }} | Starting {{ c.start_date }} |
| 🕐 **زمان** | {{ c.schedule }} | {{ c.schedule_en }} |
| 📍 **مکان** | {{ c.location }} | Tarbiat Modares University, CS Dept, Building 4th Floor, Room 3401 |

{% include section.html %}

## 🎁 مزایای شرکت در دوره | Benefits

{% capture col1 %}

{% for b in c.benefits %}
- {{ b }}
{% endfor %}

{% endcapture %}

{% capture col2 %}

{% for b in c.benefits_en %}
- {{ b }}
{% endfor %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html %}

## 🎯 هدف راهبردی | Strategic Goal

{% capture text %}

{{ c.strategic_goal }}

{{ c.strategic_goal_en }}

{% endcapture %}

{{ text | markdownify }}

{% include section.html %}

## ⚠️ نکات مهم ثبت‌نام | Important Registration Notes

{% for note in c.notes %}
> {{ note }}
{% endfor %}

{% for note in c.notes_en %}
> {{ note }}
{% endfor %}

{% include section.html %}

<div style="text-align: center; padding: 2rem 0;">

{%
  include button.html
  link=c.registration_url
  text="ثبت‌نام در دوره"
  icon="fa-solid fa-user-plus"
  tooltip="Click to register"
  style="filled"
%}

</div>
