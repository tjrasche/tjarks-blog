---
title: "Search" # in any language you want
layout: "search" # is necessary
url: "/search"
summary: "search"
params:
  fuseOpts:
     isCaseSensitive: false
     shouldSort: true
     location: 0
     distance: 1000
     threshold: 0.4
     minMatchCharLength: 0
     keys: ["title", "permalink", "summary", "content"]
---
