---
title: "Blog"
eleventyNavigation:
  key: "Blog"
  order: 2
description: This is the blog page.
body:
---
Here is a list of recent articles.

{% set postslist = collections.posts %}
{% include "postslist.njk" %}
