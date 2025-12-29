# daphnejarjoura.com

Personal website and blog built with [Hugo](https://gohugo.io) and the [Risotto](https://github.com/joeroe/risotto) theme.

## Local Development

```bash
# Preview site locally
hugo server -D

# Build for production
hugo
```

## Adding Content

### New blog post

Create a file in `content/posts/`:

```bash
hugo new posts/my-post-title.md
```

Or manually create `content/posts/my-post-title.md`:

```markdown
---
title: "My Post Title"
date: 2024-12-29
draft: false
tags: ["tag1", "tag2"]
---

Your content here...
```

### New project

Create a file in `content/projects/your-project.md`.

## Deployment

Automatically deploys to GitHub Pages on push to `main` branch.
