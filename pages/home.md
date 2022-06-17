---
layout: layouts/home.njk
title: Home for Kristin Vegh Writes
date: 2022-01-01T00:00:00.000Z
permalink: /
eleventyNavigation:
  key: Home
  order: 0
---
# Welcome

I'm Kristin. I'm a copywriter/editor. I have


## Examples of my Work

{% set postslist = collections.post %}
{% include "components/postslist.njk" %}
