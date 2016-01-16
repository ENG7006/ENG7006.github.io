---
title: Announcements
layout: inner
permalink: /announce/
---
<div>
  {% for post in site.categories['announcements'] %}
  <div class="post-list">
    <h3 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h3>

    <span class="post-date" style="font-size: small">{{ post.date | date_to_string }}. {% if post.categories.first != null %}Posted in: {% for category in post.categories %}<a href="{{ site.baseurl }}blog/categories/#{{ category }}">{{ category }}</a>{% unless forloop.last %}, {% endunless %}{% endfor %}{% endif %}.</span>

    {{ post.excerpt }}
  </div>
  {% endfor %}
</div>
