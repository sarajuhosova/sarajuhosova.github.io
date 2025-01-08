---
layout: home
title: Sára Juhošová
---

# Hello, World! ☀️

* 🇸🇰 I come from Slovakia, a tiny country in Europe with delicious food.
* 🇳🇱 I've lived in the Netherlands since 2018, when I started my bachelor in Computer Science.
* 👩‍🎓 In 2024, I started pursuing a PhD with [Jesper Cockx](https://jesper.sikanda.be/) at the [Programming Languages](https://pl.ewi.tudelft.nl/) research group.
* 🧬 My research focuses on the usability of interactive theorem provers such as [Agda](https://github.com/agda/agda/).
* 🏢 You can usually find me in office 3.E.420 at [Building 28](https://map.tudelftcampus.nl/nl/poi/wiskunde-informatica-ewi/) at the [TU Delft](https://www.tudelft.nl/).
* 💡 I like
  * *nerdy things:* 🧙 (fantasy) books 🎲 [board games](https://boardgamegeek.com/collection/user/sarantja?sort=rank&sortdir=asc&rankobjecttype=subtype&rankobjectid=1&columns=title%7Cthumbnail%7Crank%7Crating%7Cbggrating%7Ccomment%7Ccommands&geekranks=Board%20Game%20Rank&objecttype=thing&ff=1&subtype=boardgame)
  * *sporty things:*🏃‍♀️ running 🚴 cycling 🏂 snowboarding ⛸️ ice skating
  * *computer things:* 🎅 [advent of code](https://github.com/sarajuhosova/aoc) 🎮 video games
  * *unusual things:* 🍀 irish dance
  * *pretty things:* 📷 [photos](#pictures)

{% for section in site.data.sections %}

<div id="{{ section.id }}">
    <h2>{{ section.title }}</h2>

    {% include sections/{{ section.id }}.html %}
</div>

{% endfor %}
