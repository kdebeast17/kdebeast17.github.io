# kdebeast17.github.io

Personal site and blog, built with Jekyll and deployed via GitHub Pages (GitHub Actions).

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open http://127.0.0.1:4000

## Adding a post

Add a new file to `_posts/` named `YYYY-MM-DD-title.md` with front matter:

```yaml
---
layout: post
title: "My Title"
date: YYYY-MM-DD HH:MM:SS +0000
categories: general
---
```
