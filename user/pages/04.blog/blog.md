---
title: Blog
published: true
body_classes: 'header-image fullwidth'
process:
    markdown: true
    twig: false
content:
    items: '@self.children'
    limit: 5
    order:
        by: date
        dir: desc
    pagination: true
    url_taxonomy_filters: true
blog_url: blog
sitemap:
    changefreq: monthly
    priority: 1.03
feed:
    description: 'Sample Blog Description'
    limit: 10
pagination: true
---

# My Gravtastic Blog
## A tale of **awesomazing** adventures
