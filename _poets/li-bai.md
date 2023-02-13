---
title: Li Bai 李白
---
Li Bai 李白 (701 - 762) is one of the most famous poets of the High Tang 盛唐, the golden age of Chinese poetry. In his early life, participation in literature and the arts was encouraged by the emperor. However, his life ended in chaos amid the An Lushan 安祿山 rebellion. Li Bai's poetry reflects his life; he is known for his use of vivid, clear imagery interspersed with reflections on nature, solitude, and wine drinking.

##### Poems

<ul>
  {% assign filtered_posts = site.posts | where: 'author', page.title %}
  {% for post in filtered_posts %}
       <ul class="post-list">
             {% include poet-list-item.html %}
       </ul>
  {% endfor %}
</ul>