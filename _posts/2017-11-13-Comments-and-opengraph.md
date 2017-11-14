---
layout: post
comments: true
title:  "Including Comments & Open Graph"
date:   2017-11-13 10:26:00 +0100
categories: Exam 1
---

### How did i implement comments?

We have built a static site with no user input and therefore the easiest way to solve this problem is to link to someone outside like for example  [disqus.com][dq]. Disqus gives us the possibility to create “comment forums“ that we easily can link to in our own site. The users text will be written at [disqus.com][dq] but users will see it as if it happens on our site. This might sound like allot of work when every page needs to include someone else's page, but it’s actually quite easy and we don’t have to repeat the code. In my site i include comments to every post i do i the blog and the only thing I need to do for a new post is to make sure that two lines are included at the top.
“Layout: post” and  “comments: true”. Layout puts your post inside a made layout called post.html. In there we can control every post look and there we also write in disqus inside an “if”. The “if” will only open our disqus file if comments is set to true. That makes it easy for us to control which posts will have comments and which will not. The code for the comments are in a separate file so we only call for that code in post.html


[dq]: https://disqus.com/

### How did i implement Open Graph

Open Graph makes it possible to make more “living” links. Instead of a line of text we can include pictures and information about the link. This isn’t supported everywhere but facebook is one example of places that uses it today. 
To get open graph to my website i wrote a file called opengraph.html. Inside this file I tell what data is going to be used. This data gets called in the head layout which is implemented in every site. Therefore wi will get our nice open graph layout for every page. 


Sources:

Comments: [disqus.com](https://disqus.com/)  
Open Graph: [ogp.me](http://ogp.me/)

[dq]: https://disqus.com/