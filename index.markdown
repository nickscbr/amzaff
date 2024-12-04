---
layout: default
---

<h1>Welcome to Nick's Amazon Deals</h1>
<p>Discover the best Amazon deals curated just for you.</p>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
