# owenniles.github.io

Personal site and writing archive built with Jekyll and deployed with GitHub Pages.

## Local development

**Prerequisites:** [rbenv](https://github.com/rbenv/rbenv) and [ruby-build](https://github.com/rbenv/ruby-build)

```bash
# Install the pinned Ruby version
rbenv install

# Install dependencies
gem install bundler
bundle install

# Serve the site locally at http://localhost:4000
rbenv exec bundle exec jekyll serve
```

## Publish a post

Create a Markdown file in `_posts` named `YYYY-MM-DD-title.md`:

```markdown
---
title: A Clear Post Title
description: A one-sentence summary used in post lists and page metadata.
reading_time: 3
---

Write the post in Markdown.
```

Jekyll adds the post to the homepage and `/writing/` automatically. Post URLs use the format `/writing/title/`.

## Site structure

- `_layouts` contains the shared page, home, post, and resume structures.
- `_includes` contains shared navigation, analytics, and footer markup.
- `_posts` contains Markdown articles.
- `_data/resume.yml` contains the resume content.
- `assets/css/main.css` contains all site and print styling.
