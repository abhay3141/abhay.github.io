---
layout: archive
title: "Rsearch"
permalink: /research/
author_profile: true
---

<style>
a:link {
  text-decoration: none;
}
</style>

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}