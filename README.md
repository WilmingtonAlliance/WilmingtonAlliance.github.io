# Wilmington Alliance GitHub Pages

A quick GitHub Pages site for posts, images, and grab-and-go assets.

## Quick Start
1. Create a new public repo named `<username>.github.io` (or the org site `wilmingtonalliance.github.io`).
2. Upload these files to the repo root.
3. Commit and push. GitHub Pages will auto-build using the Cayman theme.
4. Visit `https://<username>.github.io` after a minute.

## Add a Post
Create a file in `_posts/` named `YYYY-MM-DD-your-title.md` with front matter:
```yaml
---
title: My Update
date: 2025-08-26
tags: [ops, data]
---
```
Write the content below the front matter in Markdown.

## Images
- Put images under `assets/img/` and reference them like `/assets/img/your-image.png`.
- The sample logo is `assets/img/wilma-logo.svg`.

## Local Preview (optional)
If you want to run Jekyll locally:
```bash
gem install bundler jekyll
bundle exec jekyll serve
# open http://127.0.0.1:4000
```