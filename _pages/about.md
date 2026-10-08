---
layout: about
title: Home
permalink: /
nav: false

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true
  more_info: >
    <div style="text-align:center; position:relative; top:-12px; font-size:0.85rem; line-height:1;">
      <p style="margin:0 !important; padding:0 !important; line-height:1 !important;">School of Computing</p>
      <p style="margin:1px 0 0 0 !important; padding:0 !important; line-height:1 !important;">Clemson University</p>
    </div>

selected_papers: false
social: true

announcements:
  enabled: false

latest_posts:
  enabled: false
---


<style>
/* Make homepage profile image smaller and center profile text */
@media (min-width: 768px) {
  .profile img {
    width: 70% !important;
    height: auto !important;
    display: block;
    margin-left: auto;
    margin-right: auto;
  }

  .profile .more-info {
    width: 70%;
    margin: 0.05rem auto 0 auto;
    text-align: center;
  }

  .profile .more-info p {
    margin: 0 !important;
    padding: 0;
    font-size: 0.78rem;
    line-height: 1.0;
  }
}
</style>

<style>
/* Move homepage profile upward on desktop */
@media (min-width: 768px) {
  .profile {
    position: relative;
    top: -20px;
  }
}
</style>

<style>
/* Home page main name */
.post-header .post-title {
  width: 100%;
  box-sizing: border-box;
  margin-bottom: 1.4rem;
  padding: 0.65rem 1rem;
  border-left: 4px solid var(--global-theme-color);
  border-radius: 7px;
  background: color-mix(
    in srgb,
    var(--global-theme-color) 9%,
    transparent
  );
  font-size: 2.15rem;
  font-weight: 500;
  line-height: 1.25;
}

/* Home page section headers, including News */
.post article h2 {
  width: 100%;
  box-sizing: border-box;
  margin-top: 2rem;
  margin-bottom: 1.2rem;
  padding: 0.55rem 1rem;
  border-left: 4px solid var(--global-theme-color);
  border-radius: 7px;
  background: color-mix(
    in srgb,
    var(--global-theme-color) 9%,
    transparent
  );
  font-size: 1.55rem;
  font-weight: 500;
  line-height: 1.3;
}
</style>

I began my M.S. in Computer Science at **Clemson University** in 2022 and completed it in 2024. I then began my Ph.D. in Computer Science at Clemson University in 2024, where I am currently a third-year Ph.D. student and a Graduate Research Assistant in the **TigerSec Lab**.

My research focuses on making AI perception systems for autonomous and safety-critical applications more **robust, secure, and trustworthy**. I work across vision-language models, adversarial machine learning, and autonomous-vehicle perception.

## News

{% for item in site.data.news limit:4 %}
<div style="margin-bottom: 0.9rem;">
  <span style="margin-right: 0.4rem;">•</span>{{ item.text }}
</div>
{% endfor %}

<p style="margin-top: 1.2rem;">
  <a href="{{ '/news/' | relative_url }}"><strong>See all news →</strong></a>
</p>
