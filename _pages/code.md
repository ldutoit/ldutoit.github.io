---
layout: archive
title: "Research Code"
permalink: /code/
author_profile: true
---
{% include base_path %}

This page is dedicated to available research repository. For teaching material, please go to [Teaching Resources](https://ldutoit.github.io/teaching/)

*In construction*

{% for post in site.code%}
{% for post in site.publications reversed %} 
{% include archive-single.html %} 
{% endfor %}{% endfor %}


