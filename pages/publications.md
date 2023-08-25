---
layout: page
title: Publications
permalink: /publications/
nav_order: 3
use_math_jax: true
last_modified_date: 2023-02-25
---

View these articles on 
[MathSciNet](http://www.ams.org/mathscinet/search/publications.html?pg1=INDI&amp;s1=805760), 
the [arXiv](https://arxiv.org/a/butterley_o_1.html)
or 
[Google Scholar](https://scholar.google.it/citations?user=GcZp0pgAAAAJ).

## Research articles

{% for publication in site.data.publications %}
- [{{ publication.title }}](../articles/{{ publication.link }}) {{ publication.authors }}. *{{ publication.journal-ref }}*,   {{ publication.year }}.
{% endfor %}

That some of these articles are published in journals affiliated to specific nations does not imply this author's approval of those nations. 
Indeed this author would prefer a world without the concept of nations.

<!-- Open data is a great idea and would me that everything required to replicate results is freely available. 
Would be great to have a link where the published versions of every document cited by this author are available. -->
