# Personal portfolio

This is a static Jekyll site for GitHub Pages. The repository root is the website source; GitHub Pages builds the `main` branch and `/` (root) directly, so publishing does not require a separate build workflow.

## Update the site

- Edit `index.md`, `about.md`, `work-experience.md`, or `contact.md` to change page content.
- Keep the YAML front matter at the top of each Markdown file. It sets the page title, description, and URL.
- Shared page structure is in `_layouts/default.html` and `_includes/`.
- Change colors, spacing, and responsive rules in `assets/css/styles.css`.
- Keep `baseurl` empty in `_config.yml` for a GitHub user site.
- The Contact page intentionally has a placeholder. Add a public method only after deciding what you want to share.

## Preview locally

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000`. The Gemfile pins Jekyll and the SEO and sitemap plugins to versions supported by GitHub Pages.

To test the production build locally:

```sh
bundle exec jekyll build
```

The generated `_site/` directory is a local build output and is not the GitHub Pages source.

## Publish with GitHub Pages

In the repository's GitHub settings, choose **Pages → Deploy from a branch → `main` → `/ (root)`**. The site URL is the GitHub user-site URL configured in `_config.yml`. GitHub Pages builds the Jekyll source on its own.

## Run Lighthouse

Open the published page in Chrome, open Developer Tools, select **Lighthouse**, choose Performance, Accessibility, Best Practices, and SEO, then generate reports for mobile and desktop. The target for each category is 90 or higher. Recheck after changes to content, layout, or assets.