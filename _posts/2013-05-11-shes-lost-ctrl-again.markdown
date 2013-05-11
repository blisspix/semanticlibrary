---
author: Fiona
comments: false
date: 2013-05-11 19:40:00
layout: post
slug: shes-lost-ctrl-again
title: She's lost ctrl again (and the post-CMS future)
---

### The post-CMS landscape

This week, I installed Drupal, then module after module after module to get it content-ready for a new project. Drupal is excellent, but it is big. Over the years, CMSs have made it easy to create content, but they have increasingly hidden the technology behind them. CMSs were certainly not giving me much motivation to get up to date with HTML5, CSS3, or jQuery.

[Development Seed](http://developmentseed.org/) is an organisation whose work I've admired for years - their open data and government projects are exceptional. In the midst of all the module installing I caught up on their [transition away from Drupal, to static HTML](http://developmentseed.org/blog/2012/07/27/build-cms-free-websites/). 

What? Static HTML? In 2013?

It actually makes a lot of sense. Complex systems have a lot of potential failure points. They require scale. I work with people in developing countries who are on slow connections. Site speed and efficiency matters. For years I've hosted my [personal portfolio](http://www.fionabradley.com), a total of 7 pages, with Wordpress - overkill. 

As more content is accessed via mobile devices including phones and tablets, it's also essential to be designing responsive sites that work cross-platform and cross-device.

### You are the controller

CMSs certainly still have a place, but feeling the need to build something, and not just install it, is exciting. I really missed the days of making a website from scratch. What I really missed was understanding how my sites really functioned, and having control over them. I had also grown frustrated with spam and injected spam in my Wordpress sites. 

### Static generator

So, what to use instead? Cue [Jekyll](http://jekyllrb.com/), a Ruby-based, blog aware site generator. Dave Cole at Development Seed [sets out the rationale](http://developmentseed.org/blog/2012/07/27/build-cms-free-websites/):

>From straight up blog and page content sites like this one to advanced map and data portals, we can use Jekyll to generate sites that rival the layout flexibility of our most complex Drupal sites with none of the development and maintenance challenges a dynamic CMS introduces. 

Jekyll works with Markdown, which is where things get really interesting. I've been generating all my HTML pages for years with Markdown in [TextMate](http://macromates.com/) ([MarkdownPad in Windows](http://markdownpad.com/)) and then pasting it into the WYSIWYG. Due to connectivity issues and code vagaries, I have never been a WYSIWYG fan. If you do feel the need for something more visual you can work with sites using [Prose.io](http://prose.io/), also from Development Seed. 

The next part is reminiscent of how creating websites used to be. Instead of FTP to upload content, you can use the version control system [Git](http://git-scm.com/) to manage content, and [host pages on GitHub](http://pages.github.com/). You can see a [prototype of my portfolio](http://blisspix.github.io/) on GitHub. 

### More than version control

GitHub is not just a place to post code, but a place to [collaborate and learn](http://www.wired.com/opinion/2013/03/github/):

>As people who were once just users become producers, they’re re-shaping the culture of open source. GitHub, I believe, is doing to open source what the internet did to the publishing industry: It’s creating a culture gap between the previous, big-project generation of open source and a newer, more amateurized generation of open source today.

GitHub is also free. Ben Balter calls this the [post-CMS world](http://ben.balter.com/2012/10/01/welcome-to-the-post-cms-world/) and points out the costs:

>Putting aside the value of time for a moment, shared hosting’s going to run you in the ballpark of $7 a month; AWS starts at $14, plus the cost of bandwidth and storage; and Jekyll, if hosted by GitHub? Free.

Yes, at this point, you need more technical skills to build a site using Jekyll than you do with Drupal or Wordpress, but this will change. Already there are frameworks like [Octopress](http://octopress.org/) which build on Jekyll. [TechHubs](http://www.techhub.com/), [user groups](http://rubyusergroups.org/) provide space and people to learn from and work with. MOOCs, open source project documentation and [tutorials](http://net.tutsplus.com/tutorials/other/building-static-sites-with-jekyll/) are improving all the time. For web entrepreneurs everywhere, being able to collaborate through TechHubs + GitHub (and other places) is a one-two punch giving the ability to learn from and build on others work. 

### The future?

I'm excited about working with Jekyll, and learning [Twitter Bootstrap](http://twitter.github.io/bootstrap/) (a CSS framework) and [jQuery](http://jquery.com/). It's not the future for every site, but it will be the future for (some of) mine.

