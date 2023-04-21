---
title: Radar
description: An opinionated collection of tools, services, and tech I'm keeping an eye on
date: 2023-04-21
dateUpdated: 2023-04-21
pinned: true
unlisted: false
draft: false
layout: "grid"
toc: true
showHeader: true
showTitle: true
showDescription: true
showMeta: false
tags:
	- radar
---

The software engineering ecosystem is a never-ending cycle of change. In my eyes, one of the most important qualities a software engineer can have is ***the desire to always be learning new things***.

Keeping up with an ever-changing industry can be difficult. New approaches, new frameworks, and new techniques are being created each and every day, so it's important to not fall behind. This can help you stay relevant as a developer.

For this reason alone, I decided to create a ***Technology Radar*** for myself so that I can help myself navigate this constant change.

A technology radar is a tool used to inspire and support engineering teams for picking the best technologies for new projects. This is an idea originating from [Thoughtworks](https://www.thoughtworks.com/radar) for mapping out the broader software engineering landscape. 

It is important to know that this is a **highly-opinionated** technology radar. This is a tool I use to help myself develop a strategy for taking on software projects by knowing which (vetted) technologies to reach for based on a specific use case. Feel free to use at your own risk.

To understand how this works, we need to define a few things first.

## Definitions

- A ***blip*** is *anything* that is determined to play a role in software engineering.
- A ***quadrant*** is a categorization of the type of ***blips***. This technology radar will use the following ***cagegories***.
	- ***Programming Languages & Frameworks*** – As the name implies, this quadrant contains *blips* that we consider to be programming *languages*, *frameworks*, and *libraries*.
	- ***Tools*** – These can be *software* tools such as *databases*, *version control systems*, *self-hosted tools* – SaaS *platforms*, *package managers*, *productivity software*, *online services*, etc. Can also include *packages* and *libraries*
	- ***Platforms*** – These are things that we build software on top of such as *mobile technologies* (e.g. Android/iOS), *operating systems* (e.g. macOS, Windows, Linux), *virtual platforms* (e.g. JVM), *hybrid clouds*, etc. This includes *engines* and *runtimes*.
	- ***Techniques*** – These include elements of the software development process such as *software architecture & design* (e.g. Microservices), *software modeling* (e.g. C4 Model), *productivity systems*, *experience design*, *testing techniques* (e.g. BDD, TDD, Page-Object Model), *infrastructure techniques* (e.g. IaaS), etc.
- A ***ring*** is a way to identify the state of research that a *blip* has undergone.
	- The ***Adopt*** ring represents blips that we think every engineering team should consider. Something that is proven to work and mature enough for use.
	- The ***Trial*** ring represents blips that are ready to use, but not as proven as blips in the *Adopt* ring. These are things that should be used on a trial basis and things you should be mindful of if you decide to ship to production.
	- The ***Assess*** ring are things to look at closely and study. Not necessarily ready for *Trial* yet, unless you think they would be a particularly good fit for you. Things that are worth keeping an eye on.
	- The ***Hold*** ring is for things that, even though they are accepted in the industry, we haven't had a good experience with. They can either be things that are flawed or things that are misused. Blips that fall into this ring are things that we wish the industry would *not* use.

***Do not make too big of a deal of the quadrants***. They are just a way to break up the radar into topic areas. It is *less* important which quadrant a *blip* falls into and *more* important which *ring* it falls into.
