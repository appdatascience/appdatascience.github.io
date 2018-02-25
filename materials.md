---
title: Учебные материалы
layout: default
---

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "materials" %}
    
      <li style="list-style-type:none">
        <h2>{{ post.title }}</h2>
        <div id="list">
        
          {{ post }}
         
        </div>
        <br/>
      </li>

    {% endif %}
  {% endfor %}
</ul>