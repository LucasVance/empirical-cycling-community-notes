### Recent

<p>
    {% for post in site.posts limit:5 %}
        {% assign pretty_category = site.data.categories[post.category] %}
        <a href="{{ site.baseurl }}{{ post.url }}">{{ pretty_category }} {{ post.title }}</a><br>
    {% endfor %}
</p>

---

### Watts Doc Series

<p>
    {% for post in site.categories["Watts Doc"] %}
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><br>
    {% endfor %}
</p>

---

### Ten Minute Tips

<p>
    {% for post in site.categories["Ten Minute Tips"] %}
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><br>
    {% endfor %}
</p>

---

### Perspectives

<p>
    {% for post in site.categories["Perspectives"] %}
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><br>
    {% endfor %}
</p>