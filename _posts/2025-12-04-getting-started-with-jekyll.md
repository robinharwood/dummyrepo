---
layout: post
title: "Getting Started with Jekyll"
date: 2025-12-04 11:00:00 -0000
categories: tutorial
tags: [jekyll, github-pages, tutorial]
---

In this post, I'll walk you through how I set up this Jekyll blog on GitHub Pages.

## Prerequisites

Before you start, make sure you have:

- A GitHub account
- Basic knowledge of Git
- (Optional) Ruby installed locally for testing

## Project Structure

A basic Jekyll site has the following structure:

```
├── _config.yml      # Site configuration
├── _posts/          # Blog posts go here
├── _layouts/        # Page templates (optional with themes)
├── _includes/       # Reusable components (optional)
├── assets/          # Images, CSS, JS files
├── index.md         # Homepage
├── about.md         # About page
└── Gemfile          # Ruby dependencies
```

## Creating a New Post

Posts live in the `_posts` directory and must follow this naming convention:

```
YEAR-MONTH-DAY-title.md
```

For example: `2025-12-04-my-first-post.md`

### Front Matter

Every post starts with front matter - YAML metadata between triple dashes:

```yaml
---
layout: post
title: "Your Post Title"
date: 2025-12-04 10:00:00 -0000
categories: category-name
tags: [tag1, tag2]
---
```

## Local Development

To run your site locally:

```bash
# Install dependencies
bundle install

# Start the local server
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

## Deploying to GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select your branch (usually `main`) as the source
4. Your site will be live at `https://username.github.io/repository-name/`

## Conclusion

Jekyll makes it easy to create and maintain a blog. With GitHub Pages, you get free hosting with automatic builds whenever you push changes.

Happy blogging!
