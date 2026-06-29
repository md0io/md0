# md0

**A git-based headless CMS. Your content stays in your GitHub repo. Your team gets a visual editor.**

md0 is a headless CMS for developers who build with MDX. Writers get a visual editor to create and update content. Developers keep full ownership: content is committed as plain `.mdx` files directly to your repository, not stored in a third-party database.

No vendor lock-in. No content migration. Your repo is the source of truth.

[Get started →](https://md0.io/cms) · [Docs](https://md0.io/docs) · [Website](https://md0.io)

---

## The problem

MDX-powered sites break down the moment you add a non-technical collaborator. Writers can't open pull requests. Developers don't want to be the bottleneck for every content change. Most headless CMSes solve this by pulling your content into their database — but then you've traded one problem for another.

md0 keeps content where it belongs: your GitHub repository. It just adds a proper editor on top.

---

## Who it's for

**Developers** building with Next.js, Astro, Gatsby, Nuxt, or any framework that reads MDX files from a repo.

**Writers and editors** who need to manage blog posts, documentation, or structured content without touching code.

---

## Features

**Visual MDX editor**
WYSIWYG editing with full GFM and MDX support. Raw markdown is always one click away — writers use the visual mode, developers can drop into source when they need to.

**GitHub-backed storage**
Every save commits directly to your repo. Your team gets full git history, branch-based drafts, and PR-based review workflows — for free, because it's just git.

**Schema-based collections**
Define field types, required fields, and content structure for each collection. Writers fill in forms; the schema enforces consistency so your content never drifts.

**Media library**
Upload images and reference them in content. No manual file paths, no separate asset hosting to configure.

**One repo, one source of truth**
Connect your GitHub repository and manage all your content from a single place. No sprawl, no sync issues — one repo drives everything.

**Zero lock-in**
Disconnect md0 and your content is untouched — plain `.mdx` files sitting in your repo, exactly as they were.

---

## Screenshots

![md0 CMS dashboard showing content collections overview](https://md0.io/screenshots/cms-dashboard.png)

![md0 visual MDX editor with WYSIWYG toolbar and raw markdown toggle](https://md0.io/screenshots/cms-editor.png)

![md0 posts list view for managing all entries in a collection](https://md0.io/screenshots/cms-posts-list.png)

![md0 collection settings panel for defining content schemas and field types](https://md0.io/screenshots/cms-collection-settings.png)

---

## How it works

1. Sign in with GitHub
2. Connect your repository
3. Define your collections and field schemas
4. Start editing — every save commits to your repo

Your static site picks up changes on the next deploy or via on-demand revalidation. Works with Next.js, Astro, Gatsby, Nuxt, and any JAMstack framework that reads files from a repository.

---

## Get started

[Sign up at md0.io →](https://md0.io/cms)

---

## License

MIT
