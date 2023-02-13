---
title: Su Shi 蘇軾
---

Many of the Tang dynasty (618 - 907) poets featured on this website were low-level provincial officials. Su Shi 蘇軾 (1037 - 1101) was by contrast a high level politician and public intellectual. The works he left behind provide detailed insights into all aspects of Song dynasty life, culture, politics and industry.

##### Poems

<ul>
  {% assign filtered_posts = site.posts | where: 'author', page.title %}
  {% for post in filtered_posts %}
       <ul class="post-list">
             {% include poet-list-item.html %}
       </ul>
  {% endfor %}
</ul>