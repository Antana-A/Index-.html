# Index-.html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>My Personal Blog</title>
    <link rel="stylesheet" href="{{ '/assets/css/main.css' | relative_url }}">
  </head>
  <body>
    <header>
      <h1>My Personal Blog</h1>
      <nav>
        <ul>
          <li><a href="{{ '/about' | relative_url }}">About</a></li>
          <li><a href="{{ '/archive' | relative_url }}">Archive</a></li>
          <li><a href="{{ '/tags' | relative_url }}">Tags</a></li>
        </ul>
      </nav>
    </header>
    <main>
      {{ content }}
    </main>
    <footer>
      <p>&copy; 2023 My Personal Blog</p>
    </footer>
  </body>
</html>
