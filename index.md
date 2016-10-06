---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

# About Me #

My name is Tom Sears and I consider myself a full-stack web developer and then some.
I was introduced to Q-Basic in the 12 years old and have been banging out code ever
since.  These days I do most of my work with web technologies, but can still duck
over to the desktop or console when I need to.

I've spent most of my post-collegiate career working with Microsoft SharePoint as
a consultant -- and not strictly in development activities.  As such, most of my
professional experience centers around parts of the Microsoft stack, but SharePoint
being the beast it is largely does things its own way. However it still uses ASP.NET
(not MVC), html, css, and javascript.

At this point I'm looking to move away from the consulting/CAD space and focus on
pure development on a product.

# Recent Projects #

## Operation Breakdown ##

![Operation Breakdown on Laptop and Phone](/assets/images/opbd.png){:class="f-left" }

Operation Breakdown
is a web-based repository for storing data gathered by parsing demo files provided
by Valve from the game Counter Strike: Global Offensive. The basic idea is that a
parsing tool goes over the demo file compiling statistics based on in-game events.
The results of that parsing are submitted to this site, where users will be able
to review a detailed breakdown of their performance during a match.

Operation Breakdown is the results of 8 months of part-time solo development, and
development continues to this day.  At the moment it is in a closed beta mode, although
the data is available for anyone to browse.

### Technologies ###

The client application was written as a C# WinForms application.  A library was
built around the [DemoInfo](https://github.com/StatsHelix/demoinfo) project to
compile the stats on a round-by-round basis.  When the client has finished parsing
a demo file, it posts the result to a REST endpoint on the site.

The site was created using the MEAN stack (mongo, express, angular, node).  Concerns
are kept strictly separated, such that nearly any of those could in principal be
swapped out for a different tech with minimal adjustments needed. It is hosted in
a 3-tier architecture using Digital Ocean droplets (Virtual Private Servers), one
for the web front end (static files, reverse proxy to application), the application
tier (REST api, minimal server-rendered pages), and the data tier.

In addition, while the logo was created as a favor from a friend, all other visual
design was done by me.

Skills highlighted in bullet point form:

* html
* css (sass/scss)
* javascript
* angular
* node
* express
* mongodb
* REST
* gulp
* Jasmine/Karma/PhantomJS
* linux (ubuntu)
* nginx
* git (gitlab, sourcetree)
* C#
* Visual Studio
* MSUnit
{: .two-column}

## tsears.net ##

That's right, the site you're looking at!.  Short and sweet so far, built using
[jekyll](https://jekyllrb.com/).

* html
* css (sass/scss)
* markdown
* jekyll
* linux (ubuntu)
* git (gitlab, GitKraken)
{: .two-column}

# Work History #

## Fusorsoft ##

## Neudesic ##

## Channelmatter ##
