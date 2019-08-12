---
layout: default
title: "Portfolio"
collection: posts
permalink: /portfolio
entries_layout: grid
classes: wide
pagination:
  enabled: true
home: true
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      - {{ post.headline }}
    </li>
  {% endfor %}
</ul>

<!-- <div class="posts">
  <div class="grid-xlarge">
    <div class="posts__container" itemscope itemtype="http://schema.org/Blog" data-columns>

      {% for post in paginator.posts %}

        {% include post-card.html %}

      {% endfor %}
    </div>
  </div>

  {% include pagination.html %}
</div> -->


<!-- Pagination links -->
<!-- <nav class="pagination">
  {% if paginator.previous_page %}
    {% if paginator.previous_page == 1 %}
      <a href="/" class="previous">&laquo;</a>
    {% else %}
      <a href="/page" class="previous">&laquo;</a>
    {% endif %}
  {% endif %}
  {% if paginator.next_page %}
    <a href="/page" class="next ">&raquo;</a>
  {% endif %}
</nav> -->