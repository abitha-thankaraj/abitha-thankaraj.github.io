---
layout: page
permalink: /publications/
title: publications
description: 
years: [2022, 2017]
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications-custom">
{% bibliography -f papers -q @*[selected=true]* %}
</div>