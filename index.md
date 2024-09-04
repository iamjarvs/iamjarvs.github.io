---
layout: default
title: Welcome to My GitHub Pages Site
---

# Welcome to My GitHub Pages Site

This is a sample home page for my GitHub Pages site using a custom theme.

## About Me

Hello! I'm a GitHub user exploring the world of custom themes and static site generators. This site is my playground for learning and experimenting with GitHub Pages.

## My Projects

Here are some of the projects I'm working on:

1. **Custom GitHub Pages Theme**: You're looking at it right now!
2. **Project Alpha**: A revolutionary app that does amazing things.
3. **Project Beta**: An open-source library for simplifying complex tasks.

## Blog Posts

Check out some of my recent blog posts:

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) ({{ post.date | date_to_string }})
{% endfor %}

## Contact Me

Feel free to reach out to me on [GitHub](https://github.com/yourusername) or [Twitter](https://twitter.com/yourusername).

---

Thanks for visiting my site! Come back soon for more updates.
