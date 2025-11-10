---
layout: page
title: Course Materials
description: Listing of course modules and topics.
---

# Course Materials

{% comment %}
Sort modules by extracting week number from title and sorting numerically in descending order
{% endcomment %}
{% assign sorted_modules = site.modules | sort: 'slug' %}
{% for module in sorted_modules reversed %}
{{ module }}
{% endfor %}
