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

<div dir="rtl" style="text-align: center;">
{{ c.target_audience }} · {{ c.format }}
</div>

<div style="text-align: center;">

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

## 📖 چشم‌انداز دوره

<div dir="rtl" style="text-align: justify;">
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

<ul style="list-style-type: disc; padding-right: 1.5rem;">
<li>مبانی معماری Transformer و مکانیزم توجه</li>
<li>روش‌های پیش‌آموزش (Pre-training) روی داده‌های عظیم</li>
<li>تنظیم دقیق (Fine-tuning) و مهندسی پرامپت</li>
<li>معیارهای ارزیابی مدل‌ها</li>
<li>استقرار مدل و چالش‌های اخلاقی</li>
</ul>

</div>

### Key Topics

- Transformer architecture fundamentals and attention mechanisms
- Pre-training methods on large-scale datasets
- Fine-tuning and prompt engineering
- Model evaluation metrics
- Model deployment and ethical challenges

<div dir="rtl" style="text-align: center; margin-top: 1rem;">
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

<ul style="list-style-type: none; padding-right: 0;">
<li>📅 <strong>تاریخ شروع:</strong> {{ c.start_date }}</li>
<li>🕐 <strong>زمان:</strong> {{ c.schedule }}</li>
<li>📍 <strong>مکان:</strong> {{ c.location }}</li>
</ul>

</div>

## 📅 Schedule & Location

- 📅 **Start Date:** {{ c.start_date }}
- 🕐 **Time:** {{ c.schedule_en }}
- 📍 **Location:** Tarbiat Modares University, CS Dept, 4th Floor, Room 3401

{% include section.html %}

<div dir="rtl">

## 🎁 مزایای شرکت در دوره

<ul style="list-style-type: disc; padding-right: 1.5rem;">
<li>مدرک و گواهی آزمایشگاه برای شرکت‌کنندگان فعال (حداقل ۸۰٪ حضور و مشارکت مؤثر)</li>
<li>شبکه‌سازی با اساتید و دانشجویان مستعد در فضایی صمیمی</li>
<li>هیچ شهریه‌ای دریافت نمی‌شود؛ یادگیری برای همه آزاد است</li>
</ul>

</div>

## 🎁 Benefits

- Lab certificate for active participants (minimum 80% attendance and effective contribution)
- Networking with faculty and talented students in a friendly environment
- No fees required; learning is free for everyone

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

<blockquote>
<p>{{ c.notes[0] }}</p>
<p>{{ c.notes[1] }}</p>
</blockquote>

</div>

## ⚠️ Important Registration Notes

> {{ c.notes_en[0] }}
> {{ c.notes_en[1] }}

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
