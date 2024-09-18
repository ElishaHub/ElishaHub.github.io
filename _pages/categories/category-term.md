---
title: "학기별 회고"
layout: archive
permalink: categories/term
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.term %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}