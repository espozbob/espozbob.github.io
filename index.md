<ul>
  {% for post in site.posts %}
   
    <li>
     {% assign date_format = "%b %-d, %Y" %}
      <span class="post-meta">{{ post.date | date: date_format }}</span>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
