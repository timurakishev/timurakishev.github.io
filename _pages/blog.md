---
layout: single
title: "[Blog]"
permalink: /blog/
author_profile: true
---

Occasional thoughts on linguistics, research, teaching, and things I find interesting. :)

{% assign sorted_posts = site.posts | sort: "date" | reverse %}
{% for post in sorted_posts %}
### [{{ post.title }}]({{ post.url | relative_url }})

{{ post.date | date: "%B %d, %Y" }}

{% if post.excerpt %}
{{ post.excerpt | strip_html | truncatewords: 35 }}
{% endif %}

{% endfor %}
