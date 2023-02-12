---
layout: poet
title: Cao Cao 曹操
---

Cao Cao 曹操 (155 - 220) is credited by some as inventing the genre of *shanshui* 山水 (landscape) poetry. However, Cao Cao was not primarily a poet, he was a warlord. He unified Northern China, but never succeeded in his ambition to unify the whole country. One of the most famous figures of early Chinese history, his status in Chinese culture is almost legendary.

##### Poems

<ul>
  {% assign filtered_posts = site.posts | where: 'author', page.short_name %}
  {% for post in filtered_posts %}
    <a href="{{ post.short_title }}">{{ post.title }}</a><br>
  {% endfor %}
</ul>