---
title: Blog
slug: blog
description: This is the blog page.
eleventyNavigation:
  key: Blog
  order: 3
---
Here is a list of recent articles.

<h2>Latest Posts</h2>

{% set postslist = collections.posts %}
{% include "postslist.njk" %}
