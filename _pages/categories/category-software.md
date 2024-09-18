---
title: "소프트웨어학과"
layout: archive
permalink: categories/software
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.software %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}