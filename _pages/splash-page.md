---
title: "UX/UI Designer."
layout: splash
permalink: /
date: 2017-08-18T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.2"
  overlay_image: /assets/images/kt-dodgers.jpg
  cta_label:
  cta_url:
  caption:
excerpt: "Cat Lover. Gamer. LA Dodgers fan. Geek."
intro:
  - excerpt:

<div class="grid__wrapper">
  <h2>Projects</h2>
  {% for post in site.portfolio %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>