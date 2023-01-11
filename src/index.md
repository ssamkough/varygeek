---
title: VaryGeek
layout: 'base.njk'
---

{% for game in collections.games %}

[{{ game.data.title }}]({{ game.url }})

{% endfor %}