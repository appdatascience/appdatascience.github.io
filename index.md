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
<a href="https://docs.google.com/forms/d/e/1FAIpQLSe2UmICzSIlqCYgWYh_11RUZK7d19jPb43tq8X4W2JV5y8ltQ/viewform" class="bigbtn">Регистрация</a>
