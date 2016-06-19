---
layout: post
title:  "Atomic Design"
date:   2015-08-11 9:00:00
tags: ["An Event Apart", "atomic design", "patterns", "process", "Brad Frost"]
categories: ["notes"]
---

## Session Notes: An Event Apart D.C. 2015


### Brad Frost - [@brad_frost]


#### What is an interface made of?
"We're not designing pages, we're desinging systems of components" - Stephen Hay

Frameworks (foundation, bootstrap, etc.) are good but there are potential pitfalls:

- One-size-fits-all
- Lookalike issues
- Potential for bloat/unneeded stuff
- Might not do everything you need
- Compatibility with existing sites
- Subscribe to someone else's style.

"Tiny Bootstraps, for every client" - Dave Rupert

Style guides or pattern libraries

- Promotes consistency
- Makes testing easier
- Creates shared vocabulary
- Future-friendly foundation

"This is absolutely how we need to be approaching web design in 2015"

Mo' patterns, mo' problems

- Time consuming to create
- Treated as a auxiliary project
- Often too abstract
- Seen only as a designer/developer tool
- Often created after a project launches
- Often incomplete/only serving present cases
- Lacking a clear methodology

#### Atomic Design

Atoms > Molecules > Organisms > Templates > Pages

Abstract -------------------------------- Concrete

Reference [------------Build-------------] Review

- Atoms: Single elements.
- Molecules: A combination of a few atoms.
- Organisms: A combination of a few molecules
- Templates: A combination of a few organisms
- Pages: Templates filled with real content

Atomic design is for user interfaces

#### Pattern Lab

What pattern lab is:

- A design system builder
- Your comprehensive interface design system
- A style guide starter kit
- A design toolkit

What pattern lab isn't:

- A UI framework
- Language, library, style, workflow dependent
- Incredibly rigid
- A CMS site generator

##### Pseudo-Patterns
Create alternatve views based on different conditions

##### Viewer
View the design agnostically, not at specific viewport sizes

##### Annotations
Keep those insights that you discovered during the wireframe phase instead of throwing them out once you get into development.

##### Lineage
What is going to be affected by a change to this pattern?


#### How do you make this work?

##### Set Expectations
"As an industry, we sell websites like paintings. Instead, we should be selling beautiful and easy access to content, agnostic of device, screen size, or context." - Dan Mall

Must get rid of waterfall process.

Development is design.

Information architecture, visual design, and development need to be engaged throughout the whole process.

##### Interface Inventory
- Round up all the unique interface patterns on your site.
- Highlight inconsistencies
- Establish scope of work
- Lay the groundwork for a future style guide

##### Establish Direction
"Ideas are meant to be ugly." - Jason Santa-Maria

Taking the shortest route possiblie to get in the enviornment where you can validate what does or does not work.

##### Roll Up Our Sleeves
Start putting content into the templates.

Collaboration and communication trump process/deliverables.




[@brad_frost]:http://twitter.com/brad_frost