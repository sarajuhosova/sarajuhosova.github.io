---
layout: home
title: Sára Juhošová
---

# Hello, World! ☀️

* 🇸🇰 I come from Slovakia, a tiny country in Europe with delicious food.
* 🇳🇱 I've lived in the Netherlands since 2018, when I started my bachelor in Computer Science.
* 👩‍💻 I enjoy puzzling over all things related to the structure and quality of software projects, <br> from programming languages to software architecture to devops.
* 🧬 In 2024, I started pursuing a PhD with [Jesper Cockx](https://jesper.sikanda.be/) on [type-driven development](#research).
* 🏢 You can usually find me in office 3.E.420 of [Building 28](https://map.tudelftcampus.nl/nl/poi/wiskunde-informatica-ewi/) at the [TU Delft](https://www.tudelft.nl/).
* 💡 I like
  * *sporty things:*
      🏃‍♀️ running 
      🚴 cycling 
      🏊‍♀️ swimming
      🏂 snowboarding 
      ⛸️ ice skating
  * *artsy things:*
      🎨 [drawing](https://www.instagram.com/sarantja/)
      📷 [photos](#pictures)
      🤘 [music](https://open.spotify.com/user/vuyp6at3dk8xr9z9mkxhyj6wa?si=4e34d35614114eb9)
  * *nerdy things:*
      🧙 (fantasy) books
      🎲 [board games](https://boardgamegeek.com/collection/user/sarantja?sort=rank&sortdir=asc&rankobjecttype=subtype&rankobjectid=1&columns=title%7Cthumbnail%7Crank%7Crating%7Cbggrating%7Ccomment%7Ccommands&geekranks=Board%20Game%20Rank&objecttype=thing&ff=1&subtype=boardgame)
      🎮 video games
  * *computer things:* 
      🎅 [advent of code](https://github.com/sarajuhosova/aoc)
  * *unusual things:*
      🍀 irish dance

{% for section in site.data.sections %}

<div class="section" id="{{ section.id }}">
    <h2>{{ section.emoji }} {{ section.title }}</h2>

    {% if section.subtitle != nil %}
      <span class="subtitle">{{ section.subtitle }}</span>
    {% endif %}

    {% include sections/{{ section.id }}.html %}
</div>

{% endfor %}
