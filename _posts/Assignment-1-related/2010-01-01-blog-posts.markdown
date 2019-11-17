---
layout: post
title: How did you implements comments to blog posts
categories: assigment-1
date: 2019-11-16
---

I decided to use Disqus's services for my website since Jekyll already seemed to have built-in support for it.
I registered a Disqus user-account. I then added some data in my _config.yml_-file. Copied the file _"disqus_comments.html"_
from the vendor-directory to my own _includes directory.

I then had to replace the code in the html-file with some code from Disqus webpage. Apparently it was outdated or something.
I then "included" the html-file in my _"post"_-layout.

_(Actually, it was already included by default but i had removed it earlier in frustration so i just re-added it again.)_
