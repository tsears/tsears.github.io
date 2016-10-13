---
layout: clean
---

![Operation Breakdown on Laptop and Phone](/assets/images/OpBdLogo.png)
{: .centered .clear}

Operation Breakdown is a web-based repository for storing data gathered by parsing
replay files (called demos) provided by Valve from the game Counter Strike: Global
Offensive. The basic idea is that a parsing tool goes over the demo file compiling
statistics based on in-game events. The results of that parsing are submitted to
this site, where users will be able to review a detailed breakdown of their performance
during a match. Also rich dashboards showing aggregate statistics allow a player
to track his performance over time.

Operation Breakdown is the results of 8 months of part-time solo development, and
development continues to this day. At the moment it is in a closed beta mode, though
the data is available for anyone to browse.  To take a quick look,
[click here](https://www.operation-breakdown.com/User/76561197973092984#/OverallData).

# How it's used #

1. Play a game of competitive matchmaking
2. Download the replay (demo) using the CS:GO game client
3. Run the Operation Breakdown client
4. Click the parse button.  The demo will be analyzed and the data submitted to
   the server.
5. Navigate to the site.  The data is immediately incorporated in to the aggregate
   statistics. The match will be shown as the left-most entry in the recent matches
   section.

# Technologies #

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
* Vagrant
{: .three .col}

![Operation Breakdown on Laptop and Phone](/assets/images/opbd.png)
{: .centered}
