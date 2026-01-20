# nievikins.github.io

## How it works

- Site generator: Jekyll (built by GitHub Pages)
- Theme: `pages-themes/cayman` via `remote_theme`
- Entry page: [index.md](index.md)
- Config: [_config.yml](_config.yml)
- Custom styles: [assets/css/custom.css](assets/css/custom.css)
- 404 page: [404.html](404.html)

## Local preview (optional)

If you want to run it locally, install Ruby + Bundler and the GitHub Pages gem.

```bash
gem install bundler
bundle init
bundle add github-pages jekyll-remote-theme
bundle exec jekyll serve --livereload
```

Then open http://localhost:4000.

## Deploy

Push to the `main` branch of the `nievikins/nievikins.github.io` repo. For a user site, GitHub Pages auto-deploys from the root of the default branch. If needed, verify in GitHub:

- Settings → Pages → Build and deployment → Source: Deploy from a branch (main / root)

## Custom domain (optional)

Add your domain in Settings → Pages and create a `CNAME` file at the repo root containing the domain.