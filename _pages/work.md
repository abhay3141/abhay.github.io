---
layout: archive
title: "Work Experience"
permalink: /work/
author_profile: true
---

{% include base_path %}

* <ins>**Accenture** - _Software Engineer, June, 2024 - Present_</ins>  
  I started my full-time at [Samsung Research Institute](https://research.samsung.com/sri-b) as a Software Engineer - Machine Learning in the Computer Vision for Devices group. I was involved with the [Penup](https://www.penup.com/main/home) team where I worked on a GAN-based model for artwork generation, improving image stylization latency and quality, weekly Supervised Object Detection, etc.


* <ins>**University of Tartu** - _Undergraduate Research Assistant, Jan 2023 - May 2024_</ins>  
  I did an internship with [SRI International](https://www.sri.com/) as an ML Researcher in the [Neuro-Symbolic Computing and Intelligence (NuSCI)](https://nusci.csl.sri.com/)  Research Group. I worked on the Robust ML side, specifically, localizing and detecting physical adversarial patches in the frequency domain.


* <ins>**Samsung Research** - _SDE Intern - Machine Learning, Aug 2020 - June 2022_</ins>  
  I did an internship with [SRI International](https://www.sri.com/) as an ML Researcher in the [Neuro-Symbolic Computing and Intelligence (NuSCI)](https://nusci.csl.sri.com/)  Research Group. I worked on the Robust ML side, specifically, localizing and detecting physical adversarial patches in the frequency domain.


* <ins>**Epilepto** - _Software Engineer Intern - Machine Learning, Summer 2019_</ins>  
  My first work experience in the industry started with Carnot Technologies as a Software Intern. It was a small startup back then. I got a chance to work on a tractor analytics app - Simha, that we deployed later on Android.
  
{% for post in site.work reversed %}
  {% include archive-single.html %}
{% endfor %}