---
title: "UX/UI Designer."
layout: splash
permalink: /
date: 2017-08-19T16:41:12+10:00
header:
  overlay_color: "#000"
  overlay_filter: "0.2"
  overlay_image: /assets/images/kt-dodgers.jpg
  cta_label:
  cta_url:
  caption:
excerpt: "Gamer. LA Dodgers fan. Mini-Painter. Human."
intro:
  - excerpt:
---

<h2>Projects</h2>

<div class="grid__wrapper">
  {% for post in site.portfolio %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
