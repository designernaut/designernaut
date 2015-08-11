---
layout: post
title:  "Design Decisions through the Lens of Performance"
date:   2015-08-10 11:30:00
tags: ["An Event Apart", "design", "performance", "Yesenia Perez-Cruz"]
categories: ["notes"]
---

## Session Notes: An Event Apart D.C. 2015


### Yesenia Perez-Cruz - [@yeseniaa]

No one sets out to build a slow site that will be tough to code and no one will want to use.

Slow, heavy sites are a result of:

- poor planning
- poor communication
- poor awareness

#### Design is a balancing act
Business goals vs user needs.

Fast, functional, light-weight vs. Beautiful, memorable, on brand

"We need a carousel to make this design pop"

"How many requests will this carousel add?"

"It's time to discuss design and performance together not as a debate, but as a collaboration that results in a beautiful user experience." - Steve Souders

Performance is how quickly you can deliver your sites and services to your audience.

Your audience wants content fast.

If we don't respect our users bandwidth, we'll lose them.

...but sites keep getting larger (avg. site is 2.16 mb)

#### Design for Performance

1. Think about performance from the very beginning.
2. Set a performance budget.
3. Communication.

#### Performance as a goal from the beginning
Performance is a design feature

Creat a UX assessment

- Identify strengths and weaknesses of the current UX

Share case studies

- Amazon observed a 1% decrease in revenue for every 100ms added to page load.
- Obama campaign team: made the new platform 60% faster which resulted in 14% increase in donation conversions.


#### Performance Budgets
Design depends largely on constraints.

A performance budget is a tangible way to start talking about performance.

Defining a performance budget:

- Browser experience (weight of files transfered)
- User experience (timing that the user experiences as they wait for the page to load)

Setting your budget:

- Look to your current pages to see how they're performing (webpagetest.org)
    - Page weight
    - Start render
    - Fully loaded
- Look to your competitors

Performance is a marketable feature.

#### Customer Goals
Aligned performance with customer goals you already have.

#### Business Goals
Increase orders, decrease customer support calls, etc.

#### When you need to add a new feature, you can:
1. Optimize an existing feature or asset on the page
2. Remove an existing feature or asset from the page.
3. Don’t add the new feature or asset.

The key is communication about the budget, and what compromises need to happen to stay within it.


#### Designing on a budget
What are my re-usable patterns? (Don't add a style you don't need)

- Smaller stylesheets.
- Less fonts.
- Less colors.

Get designs into the code earlier

- We don't know how fast it is until it's in the browser.
- Larger page weights does not necessarily mean longer wait times.


#### Use tools to help automate and monitor performance
Grunt perfbudget


#### Communicate and document
Create a style guide

- Showcase the best way to implement code & request assets.

#### Beauty vs. Function
Focus on beautiful user experiences

1. Include performance in project documents.
2. Get designs into the browser as soon as possible.
3. Test on real devices.
4. Collaborate.
5. Educate and document.