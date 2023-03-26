---
title: Latest Posts

sitemap:
    changefreq: monthly
    priority: 1.03
    
content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 4
    pagination: true

feed:
    description: Sample Blog Description
    limit: 10

pagination: true

branding:
    image:
      desktop: desktop.jpg
      mobile:  mobile.jpg
    color:
        rotate: 60
        
emblem:
    image:
      desktop: desktop.jpg
      mobile:  mobile.jpg
    color:
        rotate: 60

dominant:
    color:
        set: hsl(17,45%,40%)
    contrast:
        set: var(--primary)
        
cover: shore.jpg

---
