# Technology crap dug up from the interwebs

Random tech finds and discoveries

## Structure

- `_posts/` - Blog posts
- `_layouts/` - Page templates
- `_data/navigation.yml` - Navigation menu
- `assets/` - CSS, JS, images

## Local Development

```bash
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000

## Adding Content

### New Post
Use the `blog_post_create` tool or create a file in `_posts/`:
```
_posts/YYYY-MM-DD-title.md
```

### New Page
Use the `blog_page_create` tool or create a markdown file in root.

### New Category
Use the `blog_category_create` tool.

## Deploy

Push to GitHub and enable GitHub Pages in repository settings.
