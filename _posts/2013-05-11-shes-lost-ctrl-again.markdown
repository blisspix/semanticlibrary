---
author: Fiona
comments: false
date: 2013-05-11 19:40:00
layout: post
slug: shes-lost-ctrl-again
title: She's lost ctrl again (and the post-CMS future)
---

<h3 id="the_post_cms_landscape">The post-CMS landscape</h3>

<p>This week, I installed Drupal, then module after module after module to get it content-ready for a new project. Drupal is excellent, but it is big. Over the years, CMSs have made it easy to create content, but they have increasingly hidden the technology behind them. CMSs were certainly not giving me much motivation to get up to date with HTML5, CSS3, or jQuery.</p>

<p><a href="http://developmentseed.org/">Development Seed</a> is an organisation whose work I&#8217;ve admired for years - their open data and government projects are exceptional. In the midst of all the module installing I caught up on their <a href="http://developmentseed.org/blog/2012/07/27/build-cms-free-websites/">transition away from Drupal, to static HTML</a>. </p>

<p>What? Static HTML? In 2013?</p>

<p>It actually makes a lot of sense. Complex systems have a lot of potential failure points. They require scale. I work with people in developing countries who are on slow connections. Site speed and efficiency matters. For years I&#8217;ve hosted my <a href="http://www.fionabradley.com">personal portfolio</a>, a total of 7 pages, with Wordpress - overkill. </p>

<p>As more content is accessed via mobile devices including phones and tablets, it&#8217;s also essential to be designing responsive sites that work cross-platform and cross-device.</p>

<h3 id="you_are_the_controller">You are the controller</h3>

<p>CMSs certainly still have a place, but feeling the need to build something, and not just install it, is exciting. I really missed the days of making a website from scratch. What I really missed was understanding how my sites really functioned, and having control over them. I had also grown frustrated with spam and injected spam in my Wordpress sites. </p>

<h3 id="static_generator">Static generator</h3>

<p>So, what to use instead? Cue <a href="http://jekyllrb.com/">Jekyll</a>, a Ruby-based, blog aware site generator. Dave Cole at Development Seed <a href="http://developmentseed.org/blog/2012/07/27/build-cms-free-websites/">sets out the rationale</a>:</p>

<blockquote>
  <p>From straight up blog and page content sites like this one to advanced map and data portals, we can use Jekyll to generate sites that rival the layout flexibility of our most complex Drupal sites with none of the development and maintenance challenges a dynamic CMS introduces. </p>
</blockquote>

<p>Jekyll works with Markdown, which is where things get really interesting. I&#8217;ve been generating all my HTML pages for years with Markdown in <a href="http://macromates.com/">TextMate</a> (<a href="http://markdownpad.com/">MarkdownPad in Windows</a>) and then pasting it into the WYSIWYG. Due to connectivity issues and code vagaries, I have never been a WYSIWYG fan. If you do feel the need for something more visual you can work with sites using <a href="http://prose.io/">Prose.io</a>, also from Development Seed. </p>

<p>The next part is reminiscent of how creating websites used to be. Instead of FTP to upload content, you can use the version control system <a href="http://git-scm.com/">Git</a> to manage content, and <a href="http://pages.github.com/">host pages on GitHub</a>. You can see a <a href="http://blisspix.github.io/">prototype of my portfolio</a> on GitHub. </p>

<h3 id="more_than_version_control">More than version control</h3>

<p>GitHub is not just a place to post code, but a place to <a href="http://www.wired.com/opinion/2013/03/github/">collaborate and learn</a>:</p>

<blockquote>
  <p>As people who were once just users become producers, they’re re-shaping the culture of open source. GitHub, I believe, is doing to open source what the internet did to the publishing industry: It’s creating a culture gap between the previous, big-project generation of open source and a newer, more amateurized generation of open source today.</p>
</blockquote>

<p>GitHub is also free. Ben Balter calls this the <a href="http://ben.balter.com/2012/10/01/welcome-to-the-post-cms-world/">post-CMS world</a> and points out the costs:</p>

<blockquote>
  <p>Putting aside the value of time for a moment, shared hosting’s going to run you in the ballpark of $7 a month; AWS starts at $14, plus the cost of bandwidth and storage; and Jekyll, if hosted by GitHub? Free.</p>
</blockquote>

<p>Yes, at this point, you need more technical skills to build a site using Jekyll than you do with Drupal or Wordpress, but this will change. Already there are frameworks like <a href="http://octopress.org/">Octopress</a> which build on Jekyll. <a href="http://www.techhub.com/">TechHubs</a>, <a href="http://rubyusergroups.org/">user groups</a> provide space and people to learn from and work with. MOOCs, open source project documentation and <a href="http://net.tutsplus.com/tutorials/other/building-static-sites-with-jekyll/">tutorials</a> are improving all the time. For web entrepreneurs everywhere, being able to collaborate through TechHubs + GitHub (and other places) is a one-two punch giving the ability to learn from and build on others work. </p>

<h3 id="the_future">The future?</h3>

<p>I&#8217;m excited about working with Jekyll, and learning <a href="http://twitter.github.io/bootstrap/">Twitter Bootstrap</a> (a CSS framework) and <a href="http://jquery.com/">jQuery</a>. It&#8217;s not the future for every site, but it will be the future for (some of) mine.</p>


