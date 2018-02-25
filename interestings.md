---
title: Интересное
layout: default
---

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "interesting" %}
    
      <li style="list-style-type:none">
        <div id="list">
          {{ post }}
        </div>
        <br/>
      </li>s
    {% endif %}
  {% endfor %}
</ul>