hi! welcome!!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/writing{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
