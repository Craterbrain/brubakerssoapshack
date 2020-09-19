---
title: "Search Results"
sitemap:
  priority : 0.1
layout: "search"
---

This file exists solely to respond to /search URL with the related `search` layout template.

No content shown here is rendered, all content is based in the template layouts/page/search.html

This implementation uses Fusejs, jquery and mark.js

Search also depends on additional output content type of JSON in config.toml
```
[outputs]
  home = ["HTML", "JSON"]
```