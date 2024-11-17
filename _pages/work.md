---
layout: archive
title: "Work Experience"
permalink: /work/
author_profile: true
---

{% include base_path %}

* <ins>**Accenture** - _Software Engineer, June 2024 - Present_</ins>  
  I am currently working at [Accenture](https://www.accenture.com/in-en) as a Java Developer. In this role, I have been refactoring client Java code using the Spring framework and have gained experience working with Java, Spring, TypeScript, and AWS.


* <ins>**University of Tartu** - _Undergraduate Research Assistant, Jan 2023 - May 2024_</ins>  
  I collaborated with [Prof. Rajesh Sharma](https://scholar.google.com/citations?user=GKegbo0AAAAJ&hl=en) in the [CSS group](https://css.cs.ut.ee/) on research addressing instigating hate speech. I curated *ProvocationProbe*, a dataset of 20k tweets encompassing various controversies to analyze instigating hate speech. Further employed topic modeling to identify targeted groups in controversies and investigated distinguishing features between hate speech and instigating hate speech.


* <ins>**Samsung Research** - _SDE Intern, Summer 2023_</ins>  
  I did an internship with [SRI Bangalore](https://research.samsung.com/sri-b) in the MAC Interop division of the Network Modem Team, where I learned about data padding in compilers and the impact of additional memory usage. During my time there, I worked on optimizing memory utilization by efficiently managing this extra memory to minimize wastage. I implemented these improvements using Python to handle header files with complex C structures.


* <ins>**Epilepto** - _Machine Learning Intern, Summer 2022_</ins>  
  My first work experience was with Epilepto as a Machine Learning Intern, where I focused on seizure detection using pose detection of patients. I utilized OpenCV and Mediapipe for pose detection and developed an LSTM model with Attention mechanisms to accurately detect seizures.

{% for post in site.work reversed %}
  {% include archive-single.html %}
{% endfor %}