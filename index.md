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
<a href="https://goo.gl/forms/EGx3EoWvk4WNufL22" class="bigbtn">Регистрация</a>
