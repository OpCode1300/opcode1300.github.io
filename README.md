# Gemini Jekyll Template

A clean, modern, and SEO-friendly Jekyll template for sharing your Gemini-created pages.

## Getting Started

1.  **Fork this repository.**
2.  **Clone your forked repository** to your local machine.
3.  **Install Jekyll and dependencies:** `bundle install`
4.  **Run the Jekyll server:** `bundle exec jekyll serve`
5.  **Open your browser** to `http://localhost:4000`

## Configuration

Edit `_config.yml` to personalize your site. You'll want to change the `title`, `email`, `description`, `url`, and social media usernames.

## Creating Posts

Create new posts by adding a markdown file to the `_posts` directory. Use the following format for the filename:

`YYYY-MM-DD-your-post-title.md`

Be sure to include the front matter at the top of your post, like this:

```markdown
---
layout: post
title:  "Your Post Title"
date:   YYYY-MM-DD HH:MM:SS -0000
categories: jekyll update
seo:
  title: "Your SEO Title"
  description: "A concise and compelling description for your post."
  keywords: "relevant, keywords, for, your, post"
---
```

## SEO

This template includes the `jekyll-seo-tag` plugin for easy SEO management. You can set the `title`, `description`, and `keywords` for each page and post in the front matter. If you don't provide these, the template will fall back to the site-wide settings in `_config.yml`.

## Deployment

This template is ready to be deployed to GitHub Pages. Simply push your changes to the `main` branch of your repository, and GitHub will build and deploy your site.