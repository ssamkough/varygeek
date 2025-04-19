---
title: VaryGeek
layout: 'base.njk'
---

{% for game in collections.games | reverse %}

[{{ game.data.title }}]({{ game.url }}) (date reviewed: {{ game.data.date_reviewed }})

{% endfor %}