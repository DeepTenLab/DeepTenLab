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

<p style="text-align: center;" dir="rtl">{{ c.target_audience }} · {{ c.format }}</p>

<p style="text-align: center;">

{%
  include button.html
  link=c.registration_url
  text="ثبت‌نام در دوره"
  icon="fa-solid fa-user-plus"
  tooltip="Click to register"
  style="filled"
%}

</p>

{% include section.html %}

## 📖 چشم‌انداز دوره

<p dir="rtl" style="text-align: justify;">{{ c.vision }}</p>

---

## 📖 Course Vision

{{ c.vision_en }}

{% include section.html %}

## 📘 {{ c.book_title }}

**{{ c.book_authors }}**

### سرفصل‌های اصلی

<p dir="rtl" style="text-align: right;">

- {{ c.chapters[0] }}
- {{ c.chapters[1] }}
- {{ c.chapters[2] }}
- {{ c.chapters[3] }}
- {{ c.chapters[4] }}

</p>

### Key Topics

- {{ c.chapters_en[0] }}
- {{ c.chapters_en[1] }}
- {{ c.chapters_en[2] }}
- {{ c.chapters_en[3] }}
- {{ c.chapters_en[4] }}

<p dir="rtl" style="text-align: center; margin-top: 1rem;">این مباحث در ۵ هفته، با تلفیق تئوری، بحث گروهی و کدنویسی زنده پوشش داده خواهد شد.</p>

These topics will be covered over 5 weeks, combining theory, group discussion, and live coding.

{% include section.html %}

{% capture text %}

{{ c.session_format }}

{{ c.session_format_en }}

{% endcapture %}

{{ text | markdownify }}

{% include section.html %}

## 📅 زمان و مکان

<p dir="rtl">

- 📅 **تاریخ شروع:** {{ c.start_date }}
- 🕐 **زمان:** {{ c.schedule }}
- 📍 **مکان:** {{ c.location }}

</p>

## 📅 Schedule & Location

- 📅 **Start Date:** {{ c.start_date }}
- 🕐 **Time:** {{ c.schedule_en }}
- 📍 **Location:** Tarbiat Modares University, CS Dept, 4th Floor, Room 3401

{% include section.html %}

## 🎁 مزایای شرکت در دوره

<p dir="rtl" style="text-align: right;">

- {{ c.benefits[0] }}
- {{ c.benefits[1] }}
- {{ c.benefits[2] }}

</p>

## 🎁 Benefits

- {{ c.benefits_en[0] }}
- {{ c.benefits_en[1] }}
- {{ c.benefits_en[2] }}

{% include section.html %}

## 🎯 هدف راهبردی

<p dir="rtl" style="text-align: justify;">{{ c.strategic_goal }}</p>

## 🎯 Strategic Goal

{{ c.strategic_goal_en }}

{% include section.html %}

## ⚠️ نکات مهم ثبت‌نام

<p dir="rtl" style="text-align: right;">

> {{ c.notes[0] }}
> {{ c.notes[1] }}

</p>

## ⚠️ Important Registration Notes

> {{ c.notes_en[0] }}
> {{ c.notes_en[1] }}

{% include section.html %}

<p style="text-align: center; padding: 2rem 0;">

{%
  include button.html
  link=c.registration_url
  text="ثبت‌نام در دوره"
  icon="fa-solid fa-user-plus"
  tooltip="Click to register"
  style="filled"
%}

</p>
