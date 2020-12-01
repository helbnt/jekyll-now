---
title: The Missing Bit
Category: iamski
---
After ignoring the site (once again) for awhile, I took another stab at getting my personal domain hooked up with the Custom Domain feature that’s available in Github Pages. I think I finally, **finally** cracked it, and now I’m publishing posts from my iPad, to Github Pages, using [Jekyll](https://www.jekyllrb.com) as my CMS, [Working Copy](https://www.workingcopyapp.com) for version control, and [iA Writer](https://ia.net/writer) to actually write the posts. Huzzah!
<!--more-->

The key, missing bit in having people who visit _i-am.ski_ was setting the `A` records for my domain on my hosting provider. I’d set the `CNAME` record as described in the Github Pages docs, but I had completely missed the step [where it described](https://docs.github.com/en/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain) how to setup the `ALIAS`, `ANAME`, or `A` record. I thankfully found a [medium.com article](https://medium.com/@hossainkhan/using-custom-domain-for-github-pages-86b303d3918a) that outlined the 2 key steps needed. Once I read through that, everything clicked into place.

Now I have no excuse to write more often. Everything is working smoothly. 