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


<a href="https://scholar.google.com/citations?user=XjmA_Q4AAAAJ&hl=en&oi=ao" target="_blank"><i class="fa fa-google"></i></a>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/vjain89" target="_blank"><i class="fa fa-linkedin"></i></a>&nbsp;&nbsp;
<a href="https://twitter.com/89Vjain" target="_blank"><i class="fa fa-twitter"></i></a>&nbsp;&nbsp;