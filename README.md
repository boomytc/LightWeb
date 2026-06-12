# LightWeb

LightWeb is a static-first workspace for personal web pages: a portfolio-first home page, personal introduction, resume, blog index, and future small public pages.

## Current Shape

- `index.html` is the personal entry page.
- `pages/home/` redirects to `/` for compatibility with earlier links.
- `pages/projects/` is the portfolio overview page.
- `pages/about/` is the personal introduction page.
- `pages/resume/` is the resume page.
- `pages/blog/` is the blog index.
- `assets/styles/` stores shared CSS.
- `assets/images/` stores visual assets.
- `docs/site-map.md` records the public page plan.

## Preview

From the repository root:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://127.0.0.1:8000/
```

The pages are plain static files, so they can also be opened directly in a browser during early editing.

## Working Rule

Keep the site small and content-led. Add build tooling only when manual static pages become the bottleneck.
