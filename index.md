---
title: О школе
layout: default
---
<ul>
  {% for post in site.posts %}
    {% if post.categories contains "about" %}
    
      <li style="list-style-type:none">
        <div id="list">
          {{ post }}
         
        </div>
        <br/>
      </li>

    {% endif %}
  {% endfor %}
</ul>
<a href="/" class="bigbtn">Регистрация</a>
