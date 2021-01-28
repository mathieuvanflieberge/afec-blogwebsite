---
title: 'Blog'
layout: 'layouts/blog.html'
custom_css: 'p {font-size: 1.5em} main, footer {font-family: Roboto}'
pagination:
  data: collections.blog
  size: 4
permalink: 'blog{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html'

paginationAnchor: '#post-list'
---

Ook geïnteresseerd in webdesign? Ik plaats elke 2 weken een leuk artikeltje online! Zo kunnen we samen de wondere wereld van het coderen ontdekken.
