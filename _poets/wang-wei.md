---
title: Wang Wei 王維
permalink: /:collection/:title
---
Wang Wei 王維 (699 - 759) was one of the first Chinese poets I read. The Tang dynasty is thought to have produced some of China's best poetry throughout history, and he is widely known as one of the greatest Tang poets. His poetry effortlessly blends a naturalistic aesthetic with personal expression.

##### Poems

<ul>
  {% assign filtered_posts = site.posts | where: 'author', page.title %}
  {% for post in filtered_posts %}
       <ul class="post-list">
             {% include poet-list-item.html %}
       </ul>
  {% endfor %}
</ul>