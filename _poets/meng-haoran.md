---
title: Meng Haoran 孟浩然
permalink: /:collection/:title
---

During the Song dynasty (960 - 1279) it was fashionable to think of Meng Haoran 孟浩然 (689 - 740) and [Wang Wei 王維](/poets/wang-wei) (699 - 759) as belonging to the same school of poetry. They both wrote naturalistic poems conveyed with clarity and simplicity. Together with [Li Bai 李白](/poets/li-bai) (701 - 762) and Du Fu 杜甫 (712 – 770), these four poets are considered to be the greatest poets of the Tang dynasty.

##### Poems

<ul>
  {% assign filtered_posts = site.posts | where: 'author', page.title %}
  {% for post in filtered_posts %}
       <ul class="post-list">
             {% include poet-list-item.html %}
       </ul>
  {% endfor %}
</ul>