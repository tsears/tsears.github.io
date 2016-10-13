---
layout: clean
---

# Operation Breakdown #


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
