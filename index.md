---
layout: default.liquid
title: Home
---

{% for post in collections.posts.pages %}
#### [{{post.title}}]({{ post.permalink }})

{% if post.data.outdated %}
<div class="outdated">Outdated post</div>
{% endif %}

{{ post.excerpt }}

{{ post.published_date }} | <a href="{{post.permalink}}">Read more</a>

---

{% endfor %}
