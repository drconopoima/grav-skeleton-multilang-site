---
title: Inicio
class: home

sitemap:
    changefreq: monthly
    priority: 1.03

content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 5
    pagination: true

feed:
    description: Título de Feed
    limit: 10
---

