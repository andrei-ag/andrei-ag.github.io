---
layout: default
title: andrei-ag :: blog
lang: en
permalink: /en/
---

# Welcome

A blog about low-level programming, code emulation, and antivirus technologies.

## Latest Articles

{% for post in site.posts %}
{% if post.lang == "en" %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d.%m.%Y" }}
{% endif %}
{% endfor %}