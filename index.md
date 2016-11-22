---
layout: home
---

# About Me #

My name is Tom Sears and I consider myself a full-stack web developer, where the
stack starts at bare metal. I was introduced to Q-Basic in the 12 years old and
have been banging out code in one form or another ever since.  These days I do most
of my work with web technologies, but still duck over to the desktop or console when
I need to.

I&apos;ve spent most of my post-collegiate career working with Microsoft SharePoint as
a consultant - and not strictly in development activities.  As such, most of my
professional experience centers around parts of the Microsoft stack. SharePoint
uses ASP.NET (not MVC), html, css, and javascript, but largely takes the place of
the middle and back-end of the web development stack in favor of its own rich object
model and APIs.

At this point I&apos;m looking to move away from the consulting/CAD space and focus
on pure development on a product or service.

# Recent Projects #

## Budding Babies ##
[https://www.budding-babies.com](https://www.budding-babies.com)

Budding Babies is a site where parents can go to track the growth of their Babies
over time.  In addition to saving the raw values, it charts the various growth metrics
against the World Health Organization growth curves.

* html
* css (sass/scss)
* javascript (es6)
* angular
* node
* express
* PostgreSQL
* REST
* gulp
* linux (ubuntu)
* nginx
* Vagrant
* git (gitlab, sourcetree)
{: .three .col}

## Operation Breakdown ##
[https://www.operation-breakdown.com](https://www.operation-breakdown.com)

![Operation Breakdown on Laptop and Phone](/assets/images/opbd.png){:class="f-left" }

Operation Breakdown is a web-based repository for storing data gathered by parsing
replay files (called demos) provided by Valve from the game Counter Strike: Global
Offensive. The basic idea is that a parsing tool goes over the demo file compiling
statistics based on in-game events. The results of that parsing are submitted to
this site, where users will be able to review a detailed breakdown of their performance
during a match.

Operation Breakdown is the results of 8 months of part-time solo development, and
development continues to this day.  At the moment it is in a closed beta mode, though
the data is available for anyone to browse.

* html
* css (sass/scss)
* javascript
* angular
* node
* express
* mongodb
* REST
* gulp
* Jasmine / Karma / PhantomJS
* linux (ubuntu)
* nginx
* git (gitlab, sourcetree)
* C#
* Visual Studio
* MSUnit
* Vagrant
{: .three .col}

## tsears.net ##

That&apos;s right, the site you&apos;re looking at!.  Short and sweet so far, built using
[jekyll](https://jekyllrb.com/).

* html
* css (sass/scss)
* markdown
* jekyll
* linux (ubuntu)
* git (gitlab, GitKraken)
{: .three .col}

## Contact ##
[Source availabe on github](https://github.com/tsears/contact)

All of my projects incorporate some sort of flyout form that users can use to send
feedback or questions. I grew tired of duplicating the code to handle that, so I
created a microservice in nodejs specifically to handle the business of receiving
the data and sending me an email with the contents.

Cross Origin Resource Sharing (CORS) will be used so that I only need to run one
instance of the service without having to worry about cross-origin requests.

* nodejs
* es6
* nodeunit
* gulp
* git (github)
* microservice architecture
{: .three .col}
