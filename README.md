# butames.com

Personal blog and project site, built with [Hugo](https://gohugo.io/) and the
[Hugo Apéro](https://github.com/hugo-apero/hugo-apero) theme (included as a git submodule in `themes/hugo-apero`).

## Writing

- Blog post: create `content/blog/<slug>/index.md` (add a `featured.jpg` or `featured.png` next to it for the thumbnail).
- Project: create `content/project/<slug>/index.md` the same way.
- Front matter: `title`, `subtitle`, `date`, `excerpt`, `categories`.
- Shared images live in `static/images/` and are referenced as `/images/...`.

## Previewing locally

```
git clone --recurse-submodules https://github.com/butames/blog.github.io
hugo server        # needs Hugo extended >= 0.139
```

Then open http://localhost:1313.

## Deploying

Pushing to `main` runs `.github/workflows/hugo.yml`, which builds the site and publishes it to GitHub Pages
(Settings → Pages → Source must be set to **GitHub Actions**).
