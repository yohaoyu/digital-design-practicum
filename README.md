---
layout: minimal
title: Digital Design Practicum
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Just the Class
search_enabled: true
---
![cover_image](./assets/images/cover_image.png)
# Digital Design Practicum
{:.no_toc .fs-7 .fw-650 .lh-tight}
<a id="top"></a>

<p>
CEP 473, Department of Urban Design and Planning, University of Washington, Spring 2025 <br>
Mondays & Wednesdays, 1:30 - 3:50pm
</p>
---
<!-- Instructor -->
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}


<!--## Table of Contents
{: .no_toc}

1. TOC
{:toc}-->

## Announcements

Newest announcements below and check [all announcements](announcements.md).
{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% break %}
{% endfor %}

## Getting Started

Welcome to CEP 473, Digital Design Practicum! In this class you will learn basic skills with software tools for graphic design and communication, with a focus on their applications in urban design and planning. Besides learning the tools themselves, you will also be introduced to foundational principles of graphics. Our goal is to communicate ideas about people and place effectively and beautifully. This class is only an introduction, but it will prepare you to continue to learn digital design independently.

## Calendar

{% for module in site.modules %}
{{ module }}
{% endfor %}



<br>
<a href="#top">Back to Top</a>
