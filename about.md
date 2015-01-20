---
layout: page
title: About Me
permalink: /about/
---
{% assign me = site.data.me %}
{{ me.about }}

### My Skills

{% for skill in me.skills %}
- {{ skill.name }}: {{ skill.value }}
{% endfor %}