---
layout: about
title: Home
permalink: /
nav: false
subtitle: Third-year Ph.D. Student in Computer Science at Clemson University

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true
  more_info: >
    <p>School of Computing</p>
    <p>Clemson University</p>
    <p>Clemson, South Carolina</p>

selected_papers: false
social: true

announcements:
  enabled: false

latest_posts:
  enabled: false
---

I am a third-year Ph.D. student in Computer Science at **Clemson University** and a Graduate Research Assistant in the **TigerSec Lab**.

My research focuses on making AI perception systems for autonomous and safety-critical applications more **robust, secure, and trustworthy**. I work across vision-language models, adversarial machine learning, autonomous-vehicle perception, and efficient 3D learning.

## News

{% for item in site.data.news limit:4 %}
<div style="margin-bottom: 0.9rem;">
  <span style="margin-right: 0.4rem;">•</span>{{ item.text }}
</div>
{% endfor %}

<p style="margin-top: 1.2rem;">
  <a href="{{ '/news/' | relative_url }}"><strong>See all news →</strong></a>
</p>
