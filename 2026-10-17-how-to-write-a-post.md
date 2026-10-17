---
title: How to write a post (a cheat sheet for future me)
categories: [Guide]
---

Every post is a Markdown file in the `_posts` folder. The filename must start with the date:

```
_posts/2026-10-17-my-post-title.md
```

At the very top of the file, put this header:

```yaml
---
title: My post title
categories: [Dev]
---
```

You can give a post more than one category, like `[Dev, Notes]`. New categories appear in the sidebar automatically.

## Markdown basics

- `**bold**` → **bold**
- `*italic*` → *italic*
- `[link text](https://example.com)` → [link text](https://example.com)
- `## Heading` for a section heading
- `> quote` for a quote:

> Simple is better than complex.

## Images

Put images in an `assets/img` folder, then write:

```markdown
![description](/assets/img/photo.jpg)
```

## Code

Wrap code in three backticks and name the language:

```python
def greet(name):
    return f"Hello, {name}!"
```

That's it. Save the file, push it to GitHub, and the post goes live in a minute or two.
