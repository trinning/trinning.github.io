# Trinning website

Jekyll site for `trinning.se`.

## Local development

This site now uses a plain Jekyll setup instead of the old `github-pages` gem lockstep.

Prerequisites:

- Ruby `3.3.8` (see `.ruby-version`)
- Bundler `2.x`

Install dependencies:

```bash
bundle _2.5.22_ install
```

Start the local server:

```bash
bundle _2.5.22_ exec jekyll serve --config _config.yml,_config_dev.yml
```

Then open `http://127.0.0.1:4000`.

If your shell still picks the old Bundler `1.16.4`, either keep using the explicit `bundle _2.5.22_ ...` form or remove the stale old Bundler executable from your RubyGems user install.

## Deployment

The repo includes a GitHub Pages workflow in `.github/workflows/pages.yml`.

Recommended Pages settings:

- Source: `GitHub Actions`
- Custom domain: `trinning.se`
- Enforce HTTPS: enabled

The `CNAME` file should stay committed so the custom domain remains part of the repository.
