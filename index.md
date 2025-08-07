### Recent

{% for post in site.posts limit:5 %}
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.category }} {{ post.title }}</a>
{% endfor %}

---

### Watts Doc Series

{% for post in site.categories["Watts Doc"] %}
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}

---

### Ten Minute Tips

{% for post in site.categories["Ten Minute Tips"] %}
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}

---

### Perspectives

{% for post in site.categories["Perspectives"] %}
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}