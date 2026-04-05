---
layout: page  # 这里必须指定为你主题使用的通用页面布局，通常是 'page'
title: Personal
permalink: /personal/
---

Outside of the research lab, I believe in maintaining a balanced life through active sports, continuous learning, and strategic play. Here is a glimpse into my interests.

{% for section in site.data.personal_interests %}
  {% include interest_card.html section_title=section.section title interests_list=section.interests %}
{% endfor %}
