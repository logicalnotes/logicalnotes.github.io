# Logical Notes
> A philosophy & thinking blog built with Chirpy Jekyll theme, hosted on GitHub Pages.

## About
This is a personal blog focusing on philosophy, love thoughts, spiritual reflection and essay writing.
- Blog site: https://logicalnotes.github.io/
- Theme: Chirpy (Jekyll)
- Deploy: GitHub Actions + GitHub Pages

## Features
- Markdown post writing
- Categories & Tags classification
- Sitemap auto-generated
- Dark / Light mode switch
- Archive page for all articles

## How to add new posts
1. Create new .md file under _posts/ folder
   File name format: YYYY-MM-DD-post-title.md
2. Write front-matter at top of file:
```
---
title: "Article Title"
date: 2026-08-28 23:00:00
categories: [category-name]
tags: [tag1, tag2]
---
```

3. Write your article content in Markdown below front-matter
4. Commit & push to main branch, GitHub Actions will auto build and deploy.

## Project structure
```
logicalnotes.github.io/
├─ _posts/               # All blog articles
├─ _config.yml           # Blog main config
├─ assets/               # Images, css, js
├─ .github/workflows/    # GitHub Actions deploy script
└─ README.md
```

## Deployment
- Use GitHub Actions to build Jekyll site
- Publish to GitHub Pages
- Every commit to main branch triggers automatic build.

## Notes
1. Post file must end with .md suffix, otherwise Jekyll cannot recognize it as article.
2. date field is required in post front-matter.
3. Do not set published: false if you want article show on website.

## License
Content of blog articles is for personal sharing.
Theme Chirpy is open-source under MIT license.
