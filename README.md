# My Personal Blog

A simple Jekyll blog using the Clean Blog theme.

## Quick Start

### 1. Install Dependencies
```bash
bundle install
```

### 2. Run Local Server
```bash
bundle exec jekyll serve
```

### 3. View the Site
Open your browser and go to: `http://localhost:4000`

## File Structure

- `_config.yml` - Site configuration (title, description, social links, etc.)
- `_posts/` - Your blog posts (create new posts here)
- `_layouts/` - HTML templates for pages
- `_includes/` - Reusable HTML components
- `assets/` - CSS, JavaScript, and other assets
- `img/` - Images
- `index.html` - Homepage
- `about.html` - About page

## Creating a New Blog Post

1. Create a new file in `_posts/` with the naming format: `YYYY-MM-DD-post-title.html`
2. Add front matter at the top:

```yaml
---
layout: post
title: "Numerical Stability of Operations"
subtitle: "How do you ensure correctness of operations?"
date: 2025-10-22 14:17:00
background: '/img/posts/your-image.jpg'
---
```

3. Write your content below the front matter using HTML or Markdown

## Customization

Edit `_config.yml` to change:
- Site title and description
- Your email and social media links
- URL and baseurl settings

## License

This theme is based on [Start Bootstrap - Clean Blog](https://startbootstrap.com/themes/clean-blog-jekyll/)
