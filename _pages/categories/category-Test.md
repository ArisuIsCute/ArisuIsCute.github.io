---
title: "For Test"
layout: archive
permalink: categories/test
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.test %}
{% for post in posts %} {% include archive-line.html type=page.entries_layout %} {% endfor %}