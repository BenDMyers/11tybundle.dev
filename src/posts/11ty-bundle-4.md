---
bundleIssue: 4
eleventyComputed:
  title: "Issue {{ bundleIssue }}"
  description: "Welcome to Issue {{ bundleIssue }} of the 11ty Bundle, an occasional bundle of Eleventy releases, blog posts, sites, and resources."
date: 2023-04-18
tags:
  - 11ty Bundle
keywords: eleventy, 11ty, newsletter, roundup, news
image:
  source: "11tybundle-dev.jpg"
  alt: "the number 11 as photographed by David Monje on Unsplash"
pageId: bundle
draft: false
---

> _Sneak peek: The next issue will be a SPECIAL issue focused on posts that discuss migration from another static site generator or platform to Eleventy._

> _AND...now for an unpaid promo: [Bryan Robinson](/authors/bryan-robinson/) has written a new book called "Eleventy by Example: Learn to create powerful, performant websites with a static-first mentality." It's available for pre-order now and will be released on June 9th. [Check it out!](https://www.amazon.com/Eleventy-Example-performant-static-first-mentality-ebook/dp/B0BTPQW42M)_

## Recent releases

{% set itemType = "release" %}
{% include 'partials/bundleitems.njk' %}

## Posts from around the web

{% set itemType = "blog post" %}
{% include 'partials/bundleitems.njk' %}

## Built with Eleventy

{% set itemType = "site" %}
{% include 'partials/bundleitems.njk' %}
