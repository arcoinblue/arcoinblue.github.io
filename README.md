# My Blog

A plain, white Jekyll blog for GitHub Pages.

- **Home page** shows the newest post in full, plus a short list of earlier posts.
- **Sidebar** links to Latest, All posts (grouped by year), About, every category, and the 5 most recent posts. On phones it folds into a "☰ Menu" button.
- Built in: reading time, previous/next links, RSS feed, sitemap, link previews for social sharing, code highlighting, Korean-friendly fonts.

## Put it online (about 5 minutes)

1. On GitHub, create a new **public** repository named exactly `yourusername.github.io`.
2. Upload everything in this folder (drag the files onto the repo page → "Commit changes"). Keep the folder structure as is.
3. In the repo, go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. Wait a minute or two, then visit `https://yourusername.github.io`.

## Make it yours

- `_config.yml` — change `title`, `description`, `author`, and `url`.
- `about.md` — write your About page.
- `_posts/` — delete the two sample posts once you've read the cheat sheet.

## Writing a post

Create a file in `_posts/` named `YYYY-MM-DD-title.md`:

```markdown
---
title: My post title
categories: [Dev]
---

Post text in Markdown...
```

Commit it, and the site updates on its own. New categories appear in the sidebar automatically.
