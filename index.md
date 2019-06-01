---
---

## this is a blog

i think????

{% for post in site.posts %}
### [{{ post.title }}](/blog{{ post.url }})

_{{ post.date | date_to_string }}_

{{ post.excerpt }}

---

{% endfor %}
