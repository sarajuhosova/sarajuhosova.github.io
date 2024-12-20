---
layout: home
title: Pretty Pictures
---

# Pretty Pictures

<div class="picture-grid">

    {% for picture in site.data.pictures %}

    <div>
        <img src="/assets/images/pretty/{{ picture.source }}">
        <h3>{{ picture.caption }}</h3>

        <p class="location">{{ picture.location }}</p>
        <p class="date">{{ picture.date }}</p>
    </div>

    {% endfor %}

</div>
