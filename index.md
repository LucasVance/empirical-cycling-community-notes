---
layout: default
title: Empirical Cycling Community Notes
---

> **DISCLAIMER:**  
>
> This is an **unofficial resource** made to help listeners more easily find and revisit ideas discussed on the Empirical Cycling podcast.  
>
> These transcripts and summaries are **not reviewed, approved, or endorsed** by Empirical Cycling or Kolie Moore, and may contain inaccuracies.  
>
> The nuances of sports science can be lost in text, and current empirical understanding of the latest research may change over time.
> For the most complete and accurate information, please refer to the [original Empirical Cycling podcast episodes](https://www.empiricalcycling.com/podcast-episodes).  
>
> If you notice any errors or missing context, please [contact me](mailto:lucas.vance@protonmail.com) or make a pull request on Github.

### Recent

<p>
    {% for post in site.posts limit:5 %}
        {% assign pretty_category = site.data.categories[post.category] %}
        <a href="{{ site.baseurl }}{{ post.url }}">{{ pretty_category }} {{ post.title }}</a><br>
    {% endfor %}
</p>

### Watts Doc Series

<p>
    {% for post in site.categories["watts-doc"] %}
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><br>
    {% endfor %}
</p>

### Ten Minute Tips

<p>
    {% for post in site.categories["ten-minute-tips"] %}
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><br>
    {% endfor %}
</p>

### Perspectives

<p>
    {% for post in site.categories["perspectives"] %}
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><br>
    {% endfor %}
</p>