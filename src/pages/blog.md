---
layout: blog.njk
metaDescription: A sample Blog page listing various posts.
date: 2017-01-01
permalink: blog{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber
  }}{% endif %}/index.html
subtitle: A collection of technical blog posts and random thoughts
title: Hi...
eleventyNavigation:
  key: Blog
  order: 3
pagination:
  data: collections.post
  size: 20
---
> *For humanity, finding simplicity within its self-made complexity is the supreme irony—an act of brilliance ending in regret.*