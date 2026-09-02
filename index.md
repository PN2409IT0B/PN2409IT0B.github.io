This is my personal blog page on GitHub, created on August 26, 2026. I plan to use this to blog what I am doing on GitHub.
{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.date | date: "%B %d, %Y" }}</p>
{% endfor %}