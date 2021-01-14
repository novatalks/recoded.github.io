---
title: Workshops
layout: post
description: Coming Soon
image: assets/images/pic11.jpg
nav-menu: true
---

INTRO DESCRIPTION OR SOMETHING WE MIGHT WANT

{% for ws in site.posts %}
{% if ws.tag == "Workshop" %}
{{ws.title}}
{{ws.content}}
{%endif%}
{%endfor%}
