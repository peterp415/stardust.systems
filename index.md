---
layout: page
title: simple site
tagline: Easy websites with GitHub Pages
description: Minimal tutorial on making a simple website with GitHub Pages
---

[Github Pages](https://pages.github.com) provide a simple way to make a
website using
[Markdown](https://daringfireball.net/projects/markdown/) and
[git](https://git-scm.com).

Check out a basic example of how this works [here](https://github.com/kbroman/simple_site)

Pages Here:
{% for page in site.pages %}
- [{{ page.title }}]({{ page.url}})
{% endfor %}
