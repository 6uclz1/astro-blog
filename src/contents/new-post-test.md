---
author: 6uclz1
datetime: 2022-12-25T12:22:00Z
title: テスト
slug: テスト
featured: true
draft: false
tags:
  - docs
ogImage: ""
description: postのテスト文章
---

ここは本文？

## h2 要素は効いてる？

## テーブル要素は問題ない？

| Property          | Description                                                                               | Remark                    |
| ----------------- | ----------------------------------------------------------------------------------------- | ------------------------- |
| **こんにちは**    | Title of the post. (h1)                                                                   | required<sup>\*</sup>     |
| **_description_** | Description of the post. Used in post excerpt and site description of the post.           | default = SITE.desc       |
| **_author_**      | Author of the post.                                                                       | default = SITE.author     |
| **_datetime_**    | Published datetime in ISO 8601 format.                                                    |                           |
| **_slug_**        | Slug for the post. Usually the all lowercase title seperated in `-` instead of whtiespace | default = slugified title |
| **_featured_**    | Whether or not display this post in featured section of home page                         | default = false           |
| **_draft_**       | Mark this post 'unpublished'.                                                             | default = false           |
| **_tags_**        | Related keywords for this post. Written in array yaml format.                             |                           |
| **_ogImage_**     | OG image of the post. Useful for social media sharing and SEO.                            | default = SITE.ogImage    |
