---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---


{% include base_path %}

{% comment %} 
  Hier filtern wir die Kurse, damit nur die mit 'lang: en' angezeigt werden 
{% endcomment %}

{% assign german_projects = site.portfolio |where: "lang", "en" %}

{% for post in german_projects reversed %}
  {% include archive-single.html %}
{% endfor %}

{% comment %} 
{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

{% endcomment %}