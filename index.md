---
layout: default
title: stardust.systems Home
description: stardust.systems Home Page
skipIndex: true
---

[Github Pages](https://pages.github.com) provide a simple way to make a
website using
[Markdown](https://daringfireball.net/projects/markdown/) and
[git](https://git-scm.com).

Pages List:

{% for page in site.html_pages %}{% if page.skipIndex %}{% continue %}{% endif %}
- [{{ page.title }}]({{ page.url | relative_url }})
{% endfor %}
