<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Parthiv Varma Nandigam</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Parthiv Varma Nandigam</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About Me</a>
      <a href="posts.html">Posts</a>
    </nav>
  </header>

  <main>
    <p>This is my personal blog page on GitHub, created on August 26, 2026. I plan to use this to blog what I am doing on GitHub.</p>

    {% for post in site.posts %}
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.date | date: "%B %d, %Y" }}</p>
    {% endfor %}
  </main>
</body>
</html>