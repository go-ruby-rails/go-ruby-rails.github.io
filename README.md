<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-rails/brand/main/social/go-ruby-rails.png" alt="go-ruby-rails/go-ruby-rails.github.io" width="720"></p>

# go-ruby-rails.github.io

The organization's institutional landing page, served at
<https://go-ruby-rails.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`).

Documentation lives in a separate repository,
[go-ruby-rails/docs](https://github.com/go-ruby-rails/docs), served at
<https://go-ruby-rails.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
