---
poet: Du Fu 杜甫
---

Du Fu 杜甫 (712 – 770)  is one of China's most celebrated poets, revered for his mastery of poetry and his ability to express complex emotions and thoughts about the turbulent times he lived through. He lived during the Tang Dynasty, a period considered the golden age of Chinese poetry.

##### Poems

<ul>
  {% assign filtered_posts = site.posts | where: 'author', page.title %}
  {% for post in filtered_posts %}
       <ul class="post-list">
             {% include poet-list-item.html %}
       </ul>
  {% endfor %}
</ul>