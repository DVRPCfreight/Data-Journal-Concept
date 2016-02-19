---
layout: post
published: true
title: How does this work?
feature_image: /media/code.jpg
category: Products
tags: 
  - GIS
  - planning
  - transit
author: mruane
---

{% include JB/setup %}

### Duh, Magic. That is how!

The desire to create a blog, or any dynamic content site, often leads to a Content Management System (CMS). These systems do of course have their purposes, but can also be incredibly costly and have **a ton** of bloat. One of the best alternatives on the market is Jekyll.

Jekyll is a tool that uses a lot of fun technical nonsense to develop a static file blog from predefined templates based on content stored in Markdown files. I know, I know..."so what. That is what a CMS does right?" Wrong. A CMS ultimately relies on database to store data that is compiled by the server and sent to the client. Jekyll creates the static HTML files before they are made available on the server. 

***

### Yeah but...is Jekyll really the answer?

**I don't know!** It could be, but I don't know the full end game. 

>I just get bored on the train sometimes and figured, "I remember long ago discussing a data journal, I should learn that Jekyll thing and test it out." 

So the result? You are looking at it. 1hr and 45minutes of development for a proof of concept data journal. God bless that public transit system. 

>**But this doesn't look sleek and awesome?** Chill bro, it is a proof of concept! We can build anything from this framework. ANYTHING!!

_Disclaimer: within reason of course, this isn't NASA._

***

### What about workflow? 

Glad you asked. Work flow still needs to be defined, but that applies to any new system. The are many ways of editing Markdown files. _If you were paying attention you would know those are what store the content._ One great option that offers a friendly user interface is Prose.io. It allows users to develop content that saves directly to a Github repo and can be useful to none programmers that need help with the syntax.

About Markdown...it isn't as scary as it seems. It is a basic language for development that you can see in the demo above or [this cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). It is powerful, yet elegant. That my friend translates into a very easy learning curve.

So the process of writing a post with Prose.io:

1. Awesome, overachieving staff member decides "Hey I do cool stuff, I want to share it." They intern develop content in Markdown on Prose.io (see above)
2. The saved draft is reviewed by OCE (I guess? Beyond my pay grade)
3. Upon approval, "jekyll build" is run by the web staff and updated static files are synced to the live server.
4. Awesome, overachieving staff member celebrates their work by sharing the post with the world and buying everyone a round at happy hour.

Okay, so workflow very well may be the biggest unknown still. However, I believe this system could be deployed locally with some minor adjustments to better allocate user roles and improve this workflow.

***

### Just some things I wanted to share

This isn't perfect but I think it is a very effective way to create dynamic content. Not only that it is very scalable. Some major examples:

* [Mapbox.com/blog](Mapbox.com/blog)
* [HealthCare.gov](http://HealthCare.gov/)
* [Feeding Taxes](http://www.feedingtexas.org/)

In addition, one of the things I love about this option is that those with advanced programming knowledge can extend their content to include cool interactive material. This might be things like tables, web maps, or just a freaking awesome interactive chart.

***

#### Tech specs and Taghi-esque details
- **cost:** $0
- **server requirements:** our normal web server or host directly in Github
- **database requirements:** come on man, did you even read. No DATABASE!
- **Jekyll build environment:** local or Github
- **additional software:** none
- **final served file types:** .html, .css, .js, and any images

<br><br>

#### This was fun for me. I hope you find it useful.
_If you have questions, I might answer them._

>
>**Viva la data journal!**
>