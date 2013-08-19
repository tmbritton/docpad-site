---
layout: 'default'
title: 'WTF is DocPad?!?'
---

I'd been hearing about static site generators for a while before I finally jumped in and took one for a spin.  I downloaded and poked around a few, mostly going checking out generators I'd read about in various articles on tutorial sites.  [Jekyll](http://jekyllrb.com/ "Jekyll") in particular seems to have gained quite a bit of popularity, most likely due to it's adoption by [Github Pages](http://pages.github.com/ "Github Pages").  [Octopress](http://octopress.org/ "Octopress") is another one I looked at that seems to have quite a bit of good press.  But I don't know [Ruby](http://www.ruby-lang.org/ "Ruby"), so to extend either of these beyond creating templates, I'd have to learn a new programming language.  I finally went looking specifically for a [Node.js](http://nodejs.org/ "Node.js") static site generator and what I found with [DocPad](http://docpad.org/ "DocPad") sold me.  After years of beginning and abandoning [Wordpress](http://wordpress.org/ "Wordpress") and [Drupal](http://drupal.org "Drupal") themes I rebuilt this site using DocPad.  

##Why a Static Site Generator?##

1. **Ease of use.**  I'm maintaining this site myself.  I don't want to enter content into a rich text edit box.  I just want to use my text editor and write the HTML (or in this case, [Markdown](http://daringfireball.net/projects/markdown/ "Markdown")) as I see fit.   
2. **Security.**  There's simply less to hack.  All that's presented to the public are flat HTML files.  I don't have to worry about my Wordpress installation going out of date missing some securty updates and being hacked by some [script kiddies](http://www.urbandictionary.com/define.php?term=script+kiddie "Script Kiddies").  
3. **Speed.**  No more PHP processing time.  No more monolithic Drupal bootstraps.  No more figuring out how to work around Varnish.  Not that this is really a concern for my personal site.  My mother, my primary reader, will spend an extra two seconds to wait for the page to load.  But it's nice to have a fast site.  As a *Front End Developer* it's a matter of pride.
4. **Geekiness.**  All the cool kids on the internet are going static these days.

##Why DocPad?##

I'll let [Benjamin Lupton](http://balupton.com/ "Ben Lupton"), founder of DocPad explain:

<iframe width="640" height="480" src="//www.youtube.com/embed/hvQCXDWh7Wg" frameborder="0" allowfullscreen></iframe>

Ok, if you don't have time for a 1 hour video, I'll give my reasons.

1. ###It's Node.js!###
This means that you can use anything that is in [NPM](https://npmjs.org/ "Node Package Manager").  It fits my currently workflow very well.  I can use [SASS](http://sass-lang.com/ "Syntactically Awesome Style Sheets")/[Compass](http://compass-style.org/ "Compass") and nearly any sort of [templating engine](http://docpad.org/docs/plugins#renderers "Renderers") that I wish.  It's Javascript so I can extend it in any way I think up.  Not that I have.  But as soon as I have a great idea that hasn't been done, *it's on*!

2. ###It Doesn't Require a Node Server###
I can deploy the rendered file basically anywhere.  Github Pages, a shared hosting account, this can be deployed basically anywhere that can serve an HTTP response.  

3. ###LiveReload Built-in!###
The page refreshes and the changes are there.  It's magic.