---
layout: page
title:  "Yo-kai list"
permalink: /yokai-list/
---

| Image | Id | Name | Rank |
| ----------- | ----------- | ----------- | ----------- |
{% for y in site.data.yokai -%}
|| {{y.id}} | {{ y.name }} | {{y.rank}} |
{% endfor %}