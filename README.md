# Bukhari Lab Website

This is the website for the Bukhari Lab. The site is built with [Jekyll](https://jekyllrb.com/) and is intended to be hosted on GitHub Pages.

## Local setup

You'll need Ruby and Bundler installed. Then, from the project root:

```bash
bundle install
bundle exec jekyll serve
```

This builds the site and serves it locally at <http://localhost:4000>. Add `--livereload` to automatically refresh the browser as you edit.

## Editing content

- **Pages** are Markdown files (for example, `index.md`, `about/index.md`, `research/index.md`, `projects/index.md`, `team/index.md`, `blog/index.md`, `contact/index.md`).
- **Team members** live in `_members/` — one Markdown file per person.
- **News posts** live in `_posts/` — one Markdown file per item, named `YYYY-MM-DD-title.md`.
- **Projects and other structured data** live in `_data/` (for example, `_data/projects.yaml`).
- **Images** live in `images/` (team photos in `images/team/`, project images in `images/projects/`, news images in `images/news/`).

Site-wide settings such as the title, subtitle, and navigation links are configured in `_config.yaml`. Note that changes to `_config.yaml` require restarting `bundle exec jekyll serve`.
