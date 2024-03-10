---
poet: Tao Yuanming 陶淵明
---

Tao Yuanming 陶淵明 (365 - 427) was one of the first Chinese poets I studied. He is famous for his contribution to establishing the *tianyuan* 田園 (fields and gardens) style of poetry. While Chinese landscape poetry generally seeks to put nature at the forefront, ‘fields and gardens’ poetry tends to take place in natural spaces cultivated by humans. 

One of the earliest Chinese poets, Tao Yuanming was incorporated Buddhist, Daoist, and Confucianist themes into his poetry. He was also influenced by the *zhulin qi xian* 竹林七賢 (Seven Sages of the Bamboo Grove), a group of writers and musicians who engaged in discussions of philosophy and aesthetics with a spirit of freedom and escapism, seen as a form of silent protest against the oppressive political regime of the time.

##### Poems

<ul>
  {% assign filtered_posts = site.posts | where: 'author', page.title %}
  {% for post in filtered_posts %}
       <ul class="post-list">
             {% include poet-list-item.html %}
       </ul>
  {% endfor %}
</ul>