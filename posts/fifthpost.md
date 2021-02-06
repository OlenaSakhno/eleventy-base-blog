---
title: This is my fifth post.
description: MAKING A SIMPLE BLOG WITH THE SIMPLEST STATIC SITE GENERATOR #.
date: 2021-02-06
tags:
  - fifth post-tag
layout: layouts/post.njk
---

## Header
Each of our blog articles has the tag of post assigned to it in the front matter metadata. Eleventy provides a collection for each tag that’s been assigned, so we can access all our blog posts via the collection collections.post. The pagination metadata specifies that the variable posts will be available in the template and will contain the last 10 blog posts. In the template, we’re then iterating through each post and outputting a link to the post and outputting the date.

## Header

Each of our blog articles has the tag of post assigned to it in the front matter metadata. Eleventy provides a collection for each tag that’s been assigned, so we can access all our blog posts via the collection collections.post. The pagination metadata specifies that the variable posts will be available in the template and will contain the last 10 blog posts. In the template, we’re then iterating through each post and outputting a link to the post and outputting the date.

## Table


            
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |