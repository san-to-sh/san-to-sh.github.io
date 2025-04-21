---
layout: page
title: "Blog"
---

# My Blog

{% for post in site.posts %}
  <article>
    <h2>
      <a href="{{ post.url | relative_url }}">
        {{ post.title }}
      </a>
    </h2>
    <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time>
    {% if post.categories.size > 0 %}
      in 
      {% for category in post.categories %}
        <span>{{ category }}</span>
        {% unless forloop.last %}, {% endunless %}
      {% endfor %}
    {% endif %}
    <p>{{ post.excerpt | strip_html | truncatewords: 50 }}</p>
  </article>
{% endfor %} 