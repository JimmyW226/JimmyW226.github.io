---
layout: default
---

# Lindfield RCIA Program Readings - Scriptures

Welcome! This is where I publish my articles.

## Articles regarding Scriptures

{% for post in site.posts reversed %}
### [{{ post.title }}]({{ post.url }})

{{ post.date | date: "%B %d, %Y" }}

{{ post.excerpt }}

[Read more →]({{ post.url }})

{% endfor %}
