# Site Map

## Public Entry

| Path | Purpose | Status |
| --- | --- | --- |
| `/` | Portfolio-first personal home page and main navigation hub. | Active |
| `/pages/home/` | Compatibility redirect to `/` for earlier links. | Legacy redirect |

## Core Pages

| Path | Purpose | Status |
| --- | --- | --- |
| `/pages/projects/` | Portfolio overview for public projects, product prototypes, tools, and case-study candidates. | Active |
| `/pages/about/` | Personal introduction, background, focus areas, and contact direction. | Draft shell |
| `/pages/resume/` | Resume-style page for work history, projects, skills, and downloadable resume links later. | Draft shell |
| `/pages/blog/` | Blog index for essays, technical notes, and update posts. | Draft shell |

## First-Version Boundary

- The first version is a static personal site, not a full blog platform.
- The portfolio is the primary public surface; resume and blog can stay secondary until real content is ready.
- Pages should be useful even before a build system exists.
- Blog posts can begin as standalone HTML or Markdown notes later; do not add a generator until there are enough posts to justify it.
- Real personal details should be added deliberately and reviewed before publishing.

## Naming Rules

- Use lowercase folder names.
- Prefer stable, human-readable paths: `about`, `resume`, `blog`, `projects`.
- Each public page folder should have an `index.html`.
- Shared images belong in `assets/images/`; page-specific images can use descriptive names such as `resume-headshot.jpg` or `blog-2026-06-title.jpg`.
