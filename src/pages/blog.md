---
layout: blog.njk
metaDescription: A sample Blog page listing various posts.
date: 2017-01-01
permalink: blog{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber
  }}{% endif %}/index.html
subtitle: A collection of technical blog posts and random thoughts
title: A Simpl...
eleventyNavigation:
  key: Blog
  order: 3
pagination:
  data: collections.post
  size: 20
---
Finding simplicity in this human made complexity will be the most absurd thing that a most intelligent spieces on the earth will ever do to regret!