---
layout: post
title:  "Favicon Post"
date:   2014-06-18 12:54:44
categories: jekyll update
---

Icons
with the page content in place for a blog home page, individual blog pages, and on-page styling, it’s time to turn our attention to some of the small details that show you really care. Let’s make an icon to appear in people’s bookmarks and at the top of the browser: the favicon.

When making a favicon, it’s worth keeping in mind that it’s going to be really small. Select something, whether it’s your logo, or a symbol that represents it. In my case I chose to put together the letters SI to stand for Shop Ireland. The result is this:

favicon_example

It’s a favicon.ico file and is sized 16 by 16 pixels.
<div class="row">
<div class="col-md-6" style="background-color: #000; color:#fff;">TEST</div>
<div class="col-md-6">{% image Caribbean_reef_shark.jpg class="img-responsive" %}</div>
</div>

To make this, begin with a square canvas in Photoshop or your editor of choice. It’s usually easier to start with something bigger than 16 pixels (I would suggest about 500px by 500px), and we’ll scale it down later. Once you’ve assembled an image, the quickest way to generate the favicon itself is to upload it to Iconifier.

It will shrink the file down to 16 pixels and you can then download the resulting .ico file. Place this file in the root of your blog project.

With that made, the following line in the head of your HTML will direct the browser to look for it:

```<link rel="shortcut icon" type="image/x-icon" href="/favicon.ico>```
{% image 300x300 Caribbean_reef_shark.jpg class="img-responsive" %}
