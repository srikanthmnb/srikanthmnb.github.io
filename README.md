# my-website

A personal website built with Hugo using the PaperMod theme.

**What this repo contains**
- Hugo site source (content/, layouts/, static/, assets/)
- Theme: PaperMod (in `themes/PaperMod`)
- Build output in `public/` (generated site)

**Prerequisites**
- Install Hugo (recommended: latest stable). For theme asset processing you may need the Hugo extended binary.

**Local development**
1. From the repository root, run:

```bash
hugo server -D
```

2. Open http://localhost:1313 to preview the site. The server watches `content/`, `layouts/`, and assets for changes.

**Build for production**

```bash
hugo
```

The generated site will be written to the `public/` directory.

**Deploy**
- Deploy the contents of `public/` to your static hosting provider (GitHub Pages, Netlify, Vercel, etc.).
- For GitHub Pages: build locally (`hugo`) and push `public/` to the `gh-pages` branch, or use an action to build on push.

**Customization**
- Site configuration is in `hugo.toml`.
- Content files live under `content/` (pages, posts, gallery, etc.).
- Theme files are in `themes/PaperMod`. To customize, copy partials or layout overrides into `layouts/`.

**Useful files**
- `hugo.toml` — site configuration
- `themes/PaperMod/` — theme source and templates
- `content/` — markdown content for pages and posts


---
Created on May 30, 2026.
