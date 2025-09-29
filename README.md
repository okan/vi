# vi

A simple, fast, minimal Hugo blog.

## Quick start
- Development server:
  ```bash
  hugo serve
  ```
  - Default: http://localhost:1313

- Production build:
  ```bash
  hugo --minify
  ```
  - Output: `public/`

## Content structure
- Posts: `content/posts/`
- About page: `content/hakkimda.md`
- Static assets: `static/`
- Theme: `themes/vit/`

Create a new post:
```bash
hugo new posts/my-first-post.md
```

## Deployment (GitHub Pages)
- Workflow: `.github/workflows/hugo.yaml`
- In your repo settings, set Pages source to “GitHub Actions”.
- Push to `main` to trigger deployment.