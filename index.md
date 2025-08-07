### Recent

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.category }} {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

---

### Watts Doc Series

<ul>
  {% for post in site.categories["Watts Doc"] %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

---

### Ten Minute Tips

<ul>
  {% for post in site.categories["Ten Minute Tips"] %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

---

### Perspectives

<ul>
  {% for post in site.categories["Perspectives"] %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>