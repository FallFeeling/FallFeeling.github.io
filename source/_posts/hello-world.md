---
title: Hello World
date: 2026-06-30 00:00:00
updated: 2026-06-30 00:00:00
categories:
  - Notes
tags:
  - Hexo
  - NexT
  - GitHub Pages
description: The first test post for a Hexo + NexT blog on GitHub Pages.
---

Welcome. This is the first post of **Bilala's Blog**, built with Hexo, styled with the NexT theme, and published through GitHub Pages.

<!-- more -->

## What This Blog Is

This site is meant to be a clean personal notebook for:

- technical notes
- reading records
- project logs
- small experiments

The blog source lives locally in `D:\blog`. After writing or editing Markdown posts, pushing the repository to GitHub will trigger an automated build and update the live site.

## Publishing Flow

```bash
git add .
git commit -m "Update blog"
git push
```

GitHub Actions will install dependencies, generate the static files, and publish the site.

## Next Steps

The current post is only a smoke test. The next real step is to replace this with your own Markdown notes and tune the homepage style as your writing grows.
