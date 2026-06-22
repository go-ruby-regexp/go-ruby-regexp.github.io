<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-regexp/brand/main/social/go-ruby-regexp.png" alt="go-ruby-regexp/go-ruby-regexp.github.io" width="720"></p>

# go-ruby-regexp.github.io

The organization's institutional landing page, served at
<https://go-ruby-regexp.github.io> and built with [Hugo](https://gohugo.io). It
is a single page (custom `layouts/index.html`, phase cards driven by
`[[params.phases]]` in `hugo.toml`).

Documentation lives in a separate repository,
[go-ruby-regexp/docs](https://github.com/go-ruby-regexp/docs), served at
<https://go-ruby-regexp.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
