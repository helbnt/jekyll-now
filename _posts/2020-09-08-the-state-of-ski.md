---
title: The State of Ski
categories: iamski
---
The last several posts have all referenced my struggles to get *i-am.ski* up and running in a manner that I was striving for; namely, to be able to update this site using just my iPad Pro in the simplest manner possible. If I had built *i-am.ski* with [Wordpress](https://www.wordpress.org) or [CraftCMS](https://craftcms.com), or one of a half-dozen other available CMS frameworks, it would have been a simple matter of loading up a web browser and pointing it to the admin backend and posting from there.

But I went and got all pigheaded about this.
<!--more-->
I like trying new things, and as I’ve stated before, wanted to simplify the site as much as possible. Just my words, and not much else. With this in mind, I chose [Jekyll](https://jekyllrb.com). Jekyll doesn’t have a handy admin backend from which I can submit my entries. Each page, whether it’s a post such as this one, or a page like my [About](/about) page, is written in [Markdown](https://daringfireball.net/projects/markdown/). Which is fairly straight forward once you get the hang of it. What I **didn’t** want was a bloated and confusing admin area that I had to navigate to create just a simple blog post. Don’t get me wrong, those kinds of CMSs have their place; Two of my [other](https://www.harleyroads.com) [sites](https://www.scenicmyway.com) both use CraftCMS, and [I’ve built](https://www.wovengreenmusic.com) a [couple of other](https://www.marylandliteraryreview.com) sites on Wordpress. They’re great tools when you have a beefy website to build.

Jekyll is a static site generator, meaning there’s no database that I need to configure. Just flat files, utilizing the [Liquid](https://shopify.github.io/liquid/) templating language. And after weeks of trial and error, I finally have a workflow I’m comfortable with, with tools I enjoy using (that’s always a big plus), all from my iPad Pro, which is a great piece of technology. Here’s the breakdown:

**Hosting:** [GitHub Pages](https://pages.github.com). Quite frankly, this was the most difficult part of getting *i-am.ski* up and running. I have my [own hosting service](https://www.dreamhost.com) that I’ve been using for more than 10 years now. But after a lot of research and trial and error (mostly error), I decided to move the *i-am.ski* domain off of my hosting, and put it on GitHub Pages. The beauty of this is that Jekyll has built-in support for GitHub Pages. When I make changes to the layout, or I submit a new post, GitHub Pages runs the required updates to spit out my changes. Simple to use and, amazingly, free as well.

**Version Control:** [Working Copy](https://workingcopyapp.com). Working Copy is a git client  for iOS that does everything you would expect a desktop git client to do. There was a bit of a learning curve, but, like most things, once I started using it often to update the site, it became a lot easier to check-in files to GitHub Pages’s repositories.

**Editor:** [Textastic](https://www.textasticapp.com). I’m forever tweaking the site, and while I (think I) can update the files from Working Copy, Textastic is just a neat little text editor. Again, it’s for iOS, and supports syntax highlighting, SSH and FTP connections, and sports a host of other features.

**Writing:** [iA Writer](https://ia.net). Here’s the thing: I like apps and programs that are well designed, and get out of my way. I could, with minimal fuss, update not just the layout and code of *i-am.ski* with Textastic, but the blog posts as well. Textastic is fully capable of working with Markdown and would have been a viable solution when it came time to deciding what I wanted to use to actually write my posts. Cheaper, too. 

I am, however, a sucker for a well-designed app. And I liked the look of iA writer. At $29.99, it’s certainly one of the more expensive apps I’ve purchased. I went back and forth for a couple of weeks before finally pulling the trigger and purchasing it. Quite risky for me, given there’s not even a free trial for iOS. But I’ve not had a single moment of buyer’s remorse since.

So there you have it; GitHub Pages hosts my site. I use Working Copy to checkout and checkin the files I want to work on. Textastic for when I want to make changes to the layout or style sheet. And iA Writer for writing the content.

That’s the current state of i-am.ski. Next post, I hope to talk about the current state of SKI, as in, me, myself, and I. Stay tuned.