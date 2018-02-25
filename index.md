---
title: О школе
layout: default
---
scsdcsd
dscsdc
sdcs
d
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
