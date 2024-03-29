---
title: Guest post from Archy
author:
  name: Archy Orangecat
  email: archy@example.com
created: 2021-04-11
modifiled: 2024-03-24
slug: hey-im-archy
tags:
  - "cat-post"
  - "guest-post"
---

Hey there I'm Archy!

As I'm not the default author (that's my brother, Deux), hance I'm overriding the author's attributes for this post. I'm also changing the slug to `hey-im-archy` so the URL is more SEO friendly.

I could also have set those attributes in an index file in any folder and all articles contained in that folder and sub-folders would have defaulted to me as the author. This is called **the data cascade**, it works with any attribute and is very powerful!

I find using `@file:` to reference other [absolute](@file:/blog/hello-world/post.md) or [relative](@file:../hello-world/post.md) files very handy. It makes it easy to change permalinks without breaking links. Files should be referenced by their path relative to the content folder.

I can also use `@permalinks:` to reference any page, [like the blog](@permalink:/blog/) by its permalink. Kiss will check that the permalink is valid and will thorw an error if it's not. Permalinks are always absolute.

You can use `@file:` and `@permalink:` in any content file that ends up being transformed into HTML, and also in templates.

Writing is tiring. Let's now relax for a bit, shall we?

![Me, my couch, my life](@file:archy_guest_poster.jpg)
