---
title: Li Bai 李白
short_name: Li Bai
---
Li Bai 李白 (701 - 762) is one of the most famous poets of the High Tang 盛唐, the golden age of Chinese poetry. In his early life, participation in literature and the arts was encouraged by the emperor. However, his life ended in chaos amid the An Lushan 安祿山 rebellion. Li Bai's poetry reflects his life; he is known for his use of vivid, clear imagery interspersed with reflections on nature, solitude, and wine drinking.

##### Poems

<ul>
  {% assign filtered_posts = site.posts | where: 'author', page.short_name %}
  {% for post in filtered_posts %}
    <a href="{{ post.short_title }}">{{ post.title }}</a><br>
  {% endfor %}
</ul>