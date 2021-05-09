# Marie B Cusick's website - Instructions

Note: Edit all files using Github interface.


### The `_config.yml` file

The main things you might need to change here are:

`title: Marie B Cusick` – change this to your website's title

`description: "Behavior Change Strategist & Communications Specialist"` – change this to your website's description

`url: "https://marie-cusick.com"` - change this to your website's domain

`author_name: "Marie B Cusick"` - Author information at the bottom of the post

You can also add/remove social links at the end of the file.


### Images

Inside the `/assets/images/` folder you'll find a few images included with the theme. Add here all images you want to link/include/use in your site.


### The home page – `/index.html`

This is your website home page. You can edit some details in the Front Matter at the top of the page:

`bio` – Bio information divided in paragraphs

`services` - Services information divided in items. Each item has an icon, a title and a description

`work`: Here you have a list of categories that they will be used by filter UI. You also have a list od items, each one describes a specific work and has a category, an image, an image description (for accesibility), a title and a description.

`hireMe` - Hiring section with some basic info.


### The blog page – `/blog/index.html`

This is the blog listing page, which shows all your blog posts. You can edit the same things as on the home page to customise it for your website.


### Adding a post

If you want to add a blog post, create a Markdown file inside `_posts`. In the next chapter you can see an example blog post content. Once you save the file, the blog post will be public for everyone on your site.


### Blog post example

```
---
layout: post
title:  "Why all women should eat alone"
description: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua Ut enim..."
date:   2016-03-19
banner_preview: blog2.jpg
banner_image: blog-banner.jpg
category: Passion
tags: [tips, fashion]
---

But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. No one rejects, dislikes, or avoids pleasure itself, because it is pleasure, but because those who do not know how to pursue pleasure rationally encounter consequences that are extremely painful.

<!--more-->

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{% include image_full.html imageurl="/assets/images/blog-detail.jpg" title="Blog Desc" caption="Blog Image Desc" %}

> “Nor again is there anyone who loves or pursues or desires to obtain pain of itself, because it is pain, but because occasionally circumstances occur in which toil and pain can procure him some great pleasure. To take a trivial example, which of us ever undertakes laborious physical exercise, except to obtain some advantage from it?”
> <cite>― Haruki Murakami</cite>

### 1914 TRANSLATION BY H. RACKHAM

But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. No one rejects, dislikes, or avoids pleasure itself, because it is pleasure, but because those who do not know how to pursue pleasure rationally encounter consequences that are extremely painful.
```

### Markdown tutorial

* [Markdown basic syntax](https://www.markdownguide.org/basic-syntax/)
* [Markdown video tutorial](https://www.youtube.com/watch?v=HUBNt18RFbo)
