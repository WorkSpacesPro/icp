---
layout: default
title: notes
weight: 8
permalink: /notes/
---

{% include blog/search.html %}
{% include blog/index.html %}
<ul id="post-list">
    {% for post in paginator.posts %}
        <li>
            <a href="{{ "/" | relative_url  }}{{ post.url | remove_first: '/' }}"><aside class="dates">{{ post.date | date:"%b %d" }}</aside></a>
            <a href="{{ "/" | relative_url  }}{{ post.url | remove_first: '/' }}">{{ post.title }} <h2>{{ post.description }}</h2></a>
        </li>
    {% endfor %}
</ul>
    {% include pagination.html %}
{% endif %}
