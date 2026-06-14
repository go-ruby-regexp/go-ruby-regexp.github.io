# go-onigmo.github.io

The organization's institutional landing page, served at
<https://go-onigmo.github.io> and built with [Hugo](https://gohugo.io). It
is a single page (custom `layouts/index.html`, phase cards driven by
`[[params.phases]]` in `hugo.toml`).

Documentation lives in a separate repository,
[go-onigmo/docs](https://github.com/go-onigmo/docs), served at
<https://go-onigmo.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
