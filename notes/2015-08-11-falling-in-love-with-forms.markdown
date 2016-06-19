---
layout: post
title:  "Falling in Love with Forms"
date:   2015-08-11 10:15:00
tags: ["An Event Apart", "forms", "Aaron Gustafson "]
categories: ["notes"]
---

## Session Notes: An Event Apart D.C. 2015


### Aaron Gustafson - [@AaronGustafson]


Forms can suck a lot less.

Utilize HTML5 input types:

- Email Address
- Telephone
- Numbers
- Range
- Date
- Time

Browsers ignore what they don't understand.

ARIA for screen-readers and other assistive technology.

A button element can contain pretty much anything (within reason).

Placeholders are just that: placeholders for actual content. They are not labels!

Datalists are our friends.

#### How should we organize our forms?
Recommends order/unordered lists (helps with screen readers)

Fieldset is used to group related controls (i.e. checkboxes or radio buttons).

Focus on making the form read naturally and easily.

You can't always make an interface perfect, but you can make it usable.

#### Validation
Include 'required' on the input.

Regular expression patterns (ex., pattern="[0-9]*").

Custom error messages.

Don't forget about server-side validation. Don't ever trust just the client.






[@AaronGustafson]:http://twitter.com/AaronGustafson