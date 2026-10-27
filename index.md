---
layout: default
---

# Welcome to My Website

Welcome! This is where I publish my articles.

## My Articles

{% for post in site.posts reversed %}
### [{{ post.title }}]({{ post.url }})

{{ post.date | date: "%B %d, %Y" }}

{{ post.excerpt }}

[Read more →]({{ post.url }})

{% endfor %}
