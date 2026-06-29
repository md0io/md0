# md0

**Headless CMS for developers — your GitHub repo is the database.**

md0 lets you manage MDX content through a visual editor while storing everything in your own GitHub repository. No separate database, no vendor lock-in, no infrastructure to run.

[Website](https://md0.io) · [Docs](https://md0.io/docs) · [CMS](https://md0.io/cms)

---

## What it does

md0 connects to your GitHub repository and gives non-technical collaborators a visual editor for your MDX content — blog posts, docs, structured data — without them ever touching a file or a terminal.

You define schemas for your collections. md0 reads and writes MDX files directly to your repo. Your static site build picks them up on the next deploy. The content pipeline stays entirely within GitHub.

---

## Features

- **Visual MDX editor** — WYSIWYG editing with full MDX/GFM support; raw markdown always accessible
- **Schema-based collections** — define field types, validation, and structure for each content type
- **GitHub as the store** — commits go directly to your repo; full history, branching, and PR workflows
- **Media library** — upload and manage images; references embed directly in content
- **Multi-repo support** — connect multiple GitHub repositories from a single account
- **Zero lock-in** — your content is plain `.mdx` files; leaving means nothing to export

---

## Screenshots

![CMS Dashboard](https://md0.io/screenshots/cms-dashboard.png)

![Content Editor](https://md0.io/screenshots/cms-editor.png)

![Posts List](https://md0.io/screenshots/cms-posts-list.png)

![Collection Settings](https://md0.io/screenshots/cms-collection-settings.png)

---

## How it works

1. Sign in with GitHub
2. Connect your repository
3. Define your content collections and field schemas
4. Start editing — every save commits to your repo

Your static site (Next.js, Astro, Gatsby, or anything that reads MDX files) picks up the changes on the next build or via on-demand ISR.

---

## Tech stack

- **Frontend** — Next.js 16 App Router
- **Backend** — Express, Drizzle ORM, PostgreSQL
- **Auth** — GitHub OAuth
- **Content** — MDX files committed to your GitHub repo via the GitHub API
- **Editor** — Tiptap-based WYSIWYG with raw markdown toggle

---

## License

MIT
