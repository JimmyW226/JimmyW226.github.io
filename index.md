---
layout: default
---

# RCIA Program Readings - Scriptures

The following articles are some basic concepts about Scriptures and why and how it is important to Christian lives.

## Articles regarding Scriptures

{% for post in site.posts reversed %}
### [{{ post.title }}]({{ post.url }})

{{ post.date | date: "%B %d, %Y" }}

{{ post.excerpt }}

[Read more →]({{ post.url }})

{% endfor %}
