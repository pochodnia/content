---
title: Blog
hide_git_sync_repo_link: true
body_classes: 'header-dark header-transparent'
child_type: item
hero_classes: 'text-light title-h1h2 overlay-dark-gradient hero-large parallax'
blog_url: /blog
show_sidebar: true
show_breadcrumbs: true
show_pagination: true
content:
    items:
        - '@self.children'
    limit: 6
    order:
        by: date
        dir: desc
    pagination: true
    url_taxonomy_filters: true
bricklayer_layout: false
display_post_summary:
    enabled: false
feed:
    limit: 10
    description: 'Sample Blog Description'
sitemap:
    changefreq: monthly
pagination: true
---

# My **Open Publishing** Space
## Create, Share and Collaborate
