---
layout: home
overview: true
permalink: /

features:
- title: Simple
  text: No more databases, comment moderation, or pesky updates to install—just *your content*.
  link:
    text: How Jekyll works &rarr;
    url: docs/usage/
- title: Static
  text: "[Markdown](https://daringfireball.net/projects/markdown/), [Liquid](https://github.com/Shopify/liquid/wiki), HTML <span class='amp'>&amp;</span> CSS go in. Static sites come out ready for deployment."
  link:
    text: Jekyll template guide &rarr;
    url: docs/templates/
- title: Blog-aware
  text: Permalinks, categories, pages, posts, and custom layouts are all first-class citizens here.
  link:
    text: Migrate your blog &rarr;
    url: http://import.jekyllrb.com
    external: true

quickstart:
  text: "Get up and running *in&nbsp;seconds*."
  shell:
    title: Quick-start Instructions
    lines:
    - path: "~"
      prompt: $
      command: gem install bundler jekyll
    - path: "~"
      prompt: $
      command: jekyll new my-awesome-site
    - path: "~"
      prompt: $
      command: cd my-awesome-site
    - path: ~/my-awesome-site
      prompt: $
      command: bundle exec jekyll serve
    - output: "&#35; =&gt; Now browse to http://localhost:4000"

call_to_action:
  img:
    src: assets/img/octojekyll.png
    width: 300
    height: 251
    alt: Free Jekyll hosting on GitHub Pages
  content:
    title: "**Free hosting** with GitHub Pages"
    text: Sick of dealing with hosting companies? [GitHub Pages](https://pages.github.com/) are *powered by Jekyll*, so you can easily deploy your site using GitHub for free&mdash;[custom domain name](https://help.github.com/articles/about-supported-custom-domains/) and&nbsp;all.
    link:
      text: Learn more about GitHub Pages &rarr;
      url: https://pages.github.com/
      external: true
---

Transform your plain text into static&nbsp;websites and&nbsp;blogs.
