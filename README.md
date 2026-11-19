# joey.foo

A Hugo blog. Styles are a static CSS file, so the site builds with plain Hugo. No theme submodule, Sass, or Dart.

```bash
hugo server
```

Write posts in `content/posts/`. GitHub Actions builds `main` and deploys it to GitHub Pages.

The stylesheet in `static/css/main.css` is the Chicago7 theme (Pico CSS, the Chicago font, and its layout rules). Light and dark follow the system setting.
