---
title: Blog
eleventyNavigation:
  key: Blog
  order: 3
description: This is the blog page.
---
Here is a list of recent articles.

<h2>Latest Posts</h2>

{% set postslist = collections.posts %}
{% include "postslist.njk" %}
