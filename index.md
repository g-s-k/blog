---
---

## this is a blog

i think????

{% for post in site.posts %}
### [{{ post.title }}](/blog{{ post.url }})

{{ post.date | date_to_string }}

{{ post.excerpt }}

{% endfor %}
