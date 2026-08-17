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

<div dir="rtl" style="text-align: center;">

# {% include icon.html icon="fa-solid fa-graduation-cap" %} {{ c.title_fa }}

**{{ c.target_audience }} · {{ c.format }}**

</div>

<div dir="rtl" style="text-align: center;">

{%
  include button.html
  link=c.registration_url
  text="ثبت‌نام در دوره"
  icon="fa-solid fa-user-plus"
  tooltip="Click to register"
  style="filled"
%}

</div>

{% include section.html %}

<div dir="rtl">

## 📖 چشم‌انداز دوره

{{ c.vision }}

</div>

---

## 📖 Course Vision

{{ c.vision_en }}

{% include section.html %}

## 📘 {{ c.book_title }}

**{{ c.book_authors }}**

<div dir="rtl">

### سرفصل‌های اصلی

{% for ch in c.chapters %}
- {{ ch }}
{% endfor %}

</div>

### Key Topics

{% for ch in c.chapters_en %}
- {{ ch }}
{% endfor %}

<div dir="rtl" style="margin-top: 1rem;">

این مباحث در ۵ هفته، با تلفیق تئوری، بحث گروهی و کدنویسی زنده پوشش داده خواهد شد.

</div>

These topics will be covered over 5 weeks, combining theory, group discussion, and live coding.

{% include section.html %}

{% capture text %}

{{ c.session_format }}

{{ c.session_format_en }}

{% endcapture %}

{{ text | markdownify }}

{% include section.html %}

<div dir="rtl">

## 📅 زمان و مکان

| | جزئیات |
|---|---|
| 📅 **تاریخ شروع** | {{ c.start_date }} |
| 🕐 **زمان** | {{ c.schedule }} |
| 📍 **مکان** | {{ c.location }} |

</div>

## 📅 Schedule & Location

| | Details |
|---|---|
| 📅 **Start Date** | {{ c.start_date }} |
| 🕐 **Time** | {{ c.schedule_en }} |
| 📍 **Location** | Tarbiat Modares University, CS Dept, 4th Floor, Room 3401 |

{% include section.html %}

<div dir="rtl">

## 🎁 مزایای شرکت در دوره

{% for b in c.benefits %}
- {{ b }}
{% endfor %}

</div>

## 🎁 Benefits

{% for b in c.benefits_en %}
- {{ b }}
{% endfor %}

{% include section.html %}

<div dir="rtl">

## 🎯 هدف راهبردی

{{ c.strategic_goal }}

</div>

## 🎯 Strategic Goal

{{ c.strategic_goal_en }}

{% include section.html %}

<div dir="rtl">

## ⚠️ نکات مهم ثبت‌نام

{% for note in c.notes %}
> {{ note }}
{% endfor %}

</div>

## ⚠️ Important Registration Notes

{% for note in c.notes_en %}
> {{ note }}
{% endfor %}

{% include section.html %}

<div dir="rtl" style="text-align: center; padding: 2rem 0;">

{%
  include button.html
  link=c.registration_url
  text="ثبت‌نام در دوره"
  icon="fa-solid fa-user-plus"
  tooltip="Click to register"
  style="filled"
%}

</div>
