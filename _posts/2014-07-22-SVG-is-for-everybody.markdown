---
layout: post
title:  "SVG is for Everybody"
date:   2014-07-22 14:00:00
categories:
---

## Session Notes: An Event Apart D.C. 2014


### Chris Coyier - [@chriscoyier]

2014 is the year of SVG

SVG is flexible, sharp, small, and accessible
SVG is responsive and responsible
You can use it now, and it's easy.
SVG syntax can be **learned**!
SVG can be made from essentially anything "vector".

SVG will never replace raster graphics.

SVG is a native file format in illustrator

Just copy a vector element in illustrator, paste in the code. BOOM SVG.

How to use SVG

- SVG-as-img - put SVG in an image tag
- SVG as background-image in CSS
- Inline SVG

Three Big Advantages to Using Inline SVG:

1. Shapes are in the DOM, thus able to be controlled by CSS
2. No additional HTTP Request (it's like a data URI but better)
3. You can define once and use in multiple places

SVG has a **viewport** and a **viewBox**

Because SVG *can* be resized worry-fre, you probably *will* resize most of the time.

#### SVG Templating

Sites need an icon template system

Set up a defs block to define the things. Then call it in the HTML.

You can move it into it's own .svg file and call it. Doesn't work in IE, but there is a [workaround](https://github.com/jonathantneal/svg4everybody).

This is the idea of SVG Sprites

You can do multicolor icons which you can't really do with icon fonts.

Responsive icons - Media Queries in CSS + SVG

[UseIconic.com](UseIconic.com)

#### Build Tools

[icomoon.io](icomoon.io) - output as svg

You can use Grunt or Gulp to help automate

#### SVG vs. Icon Fonts

SVG wins in almost every way, except for backwards compatibility in IE.

#### Fallbacks

1. Do Nothing
2. [Picturefill](http://scottjehl.github.io/picturefill/)
3. [SVG for Everybody](https://github.com/jonathantneal/svg4everybody)

#### Accessibility

- Use Inline SVG
- ARIA Roles
- Use text when possible

#### SVG Filters & Blend Modes

#### Animate SVG

- [Snap.svg](http://snapsvg.io/)




[@chriscoyier]:http://twitter.com/chriscoyier