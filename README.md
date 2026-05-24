# BrianReymore.com Astro Starter

A fast, editorial Astro site for Cloudflare Pages.

## Local setup

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

Cloudflare Pages settings:

- Framework preset: Astro
- Build command: `npm run build`
- Build output directory: `dist`
- Node version: 20 or newer

## Add a new essay

Create a Markdown file in:

```txt
src/content/essays/my-essay-slug.md
```

Use this frontmatter:

```md
---
title: "Essay Title"
subtitle: "Optional subtitle"
description: "One or two sentence summary."
pubDate: 2026-05-23
featured: false
tags: ["power", "home"]
---

Essay body here.
```
