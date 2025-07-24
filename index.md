---
layout: splash
title: Blah Blah Blah Something Here
permalink: /
header:
  overlay_image: https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=1600&q=80
excerpt: "And a subtitle"
---

# Hello and welcome 👋

This is a sample portfolio site built using the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme. Explore projects, writing, and more below.

---
This should show today's date: {{ site.time | date: "%Y-%m-%d" }}


{% include feature_row.html id="intro" type="center" %}

<p>This is a sanity check: the feature_row is loaded above 👆</p>

<p>DEBUG: intro = {{ site.data.feature_row.intro | inspect }}</p>


{% assign debug = site.data.feature_row %}
{{ debug | inspect }}