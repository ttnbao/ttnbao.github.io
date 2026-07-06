# Tingnan Bao Academic Homepage

Jekyll academic homepage for GitHub Pages.

## Publish on GitHub Pages

1. Create a repository named `your-github-username.github.io`.
2. Copy these files into that repository.
3. Commit and push to the `main` branch.
4. In GitHub, open `Settings -> Pages`, set `Build and deployment` to `GitHub Actions`, and use the included workflow.

The included workflow builds the site with Ruby 3.3 and Jekyll. For local preview, use a Ruby 3.x environment:

```bash
bundle install
bundle exec jekyll serve
```

## Files

- `_config.yml` - site metadata and GitHub Pages settings
- `_data/profile.yml` - editable research, publication, experience, and service data
- `_layouts/default.html` - shared page shell
- `.github/workflows/pages.yml` - GitHub Pages deployment workflow
- `.ruby-version` - local Ruby version hint
- `index.html` - homepage template
- `assets/css/main.css` - responsive styling
- `assets/js/main.js` - current year helper
- `assets/research-network.png` - homepage visual

Add ORCID and GitHub links once those public URLs are finalized.
