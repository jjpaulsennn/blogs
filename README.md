# Perch Blog Staging

This repository is used to draft and review blog posts before moving them into the main Perch website repository.

## Workflow

1. Create a new branch for each article using `blog/<slug>`.
2. Add the finished post as a Markdown file in `posts/`.
3. Open a pull request into `main`.
4. Review the article, metadata, SEO copy, and formatting.
5. Copy or cherry-pick the approved post into the main Perch repository.

## Perch Blog Format

Each post uses YAML frontmatter followed by Markdown content.

Required frontmatter:

- `date` — YYYY-MM-DD
- `thumbnail` — path such as `/blog/thumbnails/example.jpg`
- `title`
- `author`
- `description`
- `readTime` — estimated minutes

Use `POST_TEMPLATE.md` as the base for new articles.
