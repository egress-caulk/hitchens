---
title: Meng Haoran 孟浩然
short_name: Meng Haoran
---

During the Song dynasty (960 - 1279) it was fashionable to think of Meng Haoran 孟浩然 (689 - 740) and [Wang Wei](/poets/wang-wei) 王維 (699 - 759) as belonging to the same school of poetry. They both wrote naturalistic poems conveyed with clarity and simplicity. Together with [Li Bai](/poets/li-bai) 李白 (701 - 762) and Du Fu 杜甫 (712 – 770), these four poets are considered to be the greatest poets of the Tang dynasty.

##### Poems

<ul>
  {% assign filtered_posts = site.posts | where: 'author', page.short_name %}
  {% for post in filtered_posts %}
    <a href="{{ post.short_title }}">{{ post.title }}</a><br>
  {% endfor %}
</ul>