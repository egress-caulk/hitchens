---
poet: Xie Lingyun 謝靈運
---

Xie Lingyun 謝靈運 (385 - 483) is widely considered to be one of the first Chinese landscape poets, and blended themes of early Buddhist, Daoist, and Confucian thought into his poetry. Born into a noble family, Xie suffered from a string of demotions and ended up living in exile, where he wrote about the wild Southern landscape.

##### Poems

<ul>
  {% assign filtered_posts = site.posts | where: 'author', page.title %}
  {% for post in filtered_posts %}
       <ul class="post-list">
             {% include poet-list-item.html %}
       </ul>
  {% endfor %}
</ul>