# My Blog

A personal blog built with Jekyll and hosted on GitHub Pages.

## 🚀 Quick Start

### Local Development

1. **Install Ruby** (if not already installed)

2. **Install dependencies:**
   ```bash
   bundle install
   ```

3. **Run the local server:**
   ```bash
   bundle exec jekyll serve
   ```

4. **View your site** at `http://localhost:4000/dummyrepo/`

### Deploy to GitHub Pages

1. Push your changes to the `main` branch
2. Go to **Settings → Pages** in your repository
3. Set source to `main` branch
4. Your site will be available at `https://robinharwood.github.io/dummyrepo/`

## 📁 Project Structure

```
├── _config.yml          # Site configuration
├── _posts/              # Blog posts (YYYY-MM-DD-title.md)
├── assets/css/          # Custom styles
├── index.md             # Homepage
├── about.md             # About page
├── Gemfile              # Ruby dependencies
└── .gitignore           # Git ignore rules
```

## ✍️ Creating a New Post

Create a new file in `_posts/` with the format `YYYY-MM-DD-title.md`:

```markdown
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS -0000
categories: your-category
tags: [tag1, tag2]
---

Your content here...
```

## 🎨 Customization

- **Site settings:** Edit `_config.yml`
- **Styling:** Modify `assets/css/style.scss`
- **Theme:** Using [Minima](https://github.com/jekyll/minima) (default Jekyll theme)

## 📚 Resources

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Minima Theme](https://github.com/jekyll/minima)