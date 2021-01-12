---
layout: page
title: Home
nav_order: 1
description: A week-to-week description of the content covered in the course.
---

# Data Engineering
{: .mb-2 }
UC Berkeley, Spring 2021
{: .mb-0 .fs-6 .text-grey-dk-000 }

<div>

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}

</div>

This website is under construction. Check out <a href="https://docs.google.com/document/d/1hXcZY9OKvAbHDMBZnjYBZ08KM8Sry6TsMEno0mJt5tI/edit"> this document </a> for class information.
