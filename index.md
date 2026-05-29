---
layout: default
title: andrei-ag :: блог
lang: ru
---

# Добро пожаловать

Блог о низкоуровневом программировании, эмуляции кода и антивирусных технологиях.

## Последние статьи

{% for post in site.posts %}
{% if post.lang == "ru" %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d.%m.%Y" }}
{% endif %}
{% endfor %}