---
author: justin
title: November Update
description: Our documentation center, a first look at Stripe Terminal, and a list of what's left to do ahead of the launch of SportKeeper. 
featured_image: /assets/img/sections/november-update-photo.jpg
permalink: /posts/4-november-update
date: 2018-11-17
---

We're finally thawing out here at 4200 ft in the Blue Ridge Mountains. The last couple of days we've been frozen in an ice storm. While cooped up, I've been working to get a few final pieces of the software in place. I have a break from things, so I wanted to take a moment to give an update on where we're at so far.

###### **Business Formation**
We've officially formed an L.L.C. in the state of North Carolina. This is amongst the boring parts of building a startup. You don't really see the name of the business anywhere, and if you do it's mostly generalized. I don't think we're a boring company. In fact our upcoming manifesto will cover this in great detail.

What I **do** know, is that we make some freakin great software. So it was only fitting that the name of the startup be *Great Freakin Software Co*.

###### **Stripe Terminal**
Our software platform contains a point-of-sale (P.O.S.) component utilizing the yet-to-be released [Stripe Terminal](https://stripe.com/terminal) (currently in an invitation only beta[^1]). Two requests and a couple tweets later, my persistence paid off, and they invited me! After the purchase of a $300 card reader and a couple days in code, we have a fully working [P.O.S. component](https://docs.sport-keeper.com/hardware/stripe-terminal) for Sport Keeper. It's honestly a big weight off my shoulders to have this feature working and operational. 

While the option to manually enter card numbers exists, it was important to support physically swiping cards in order to reduce human error. It also sets the stage for us to build some really cool stuff in the future.

###### **Documentation Center**
The documentation for SportKeeper is live at [https://docs.sport-keeper.com](https://docs.sport-keeper.com). Feel free to have a poke around and explore the various components. The *Facility Components* side menu was documented to resemble what the actual UI looks like. So those headings appear in order of how they're listed within the application. There's a lot of pages in the documentation that are still empty, but we're working to get this completed before launch.

###### **What's Left to Do?**
There's not a whole heck of a lot left to do, at least as far as the software platform goes. The biggest pieces left are to finish the A.C.H. billing implementation, and some general house keeping. The dashboard is still rather empty, but I'm planning to leave this empty during the beta while gathering feedback.

Beyond that we still have to build the logic for actually selling Sport Keeper like subscriptions and marketing pages, but right now I'm just focused on getting the software finished, and getting feedback.

###### **When's the Launch?**
We're looking at a launch date of early 2019. This is mostly due to waiting for the public release of Stripe Terminal. If you're interested in getting on board early, we can arrange for your facility to purchase a card reader so you can be ahead of the curve.

In the meantime, please [request an invitation](https://sport-keeper.com/beta) to our beta! Help test the software and provide feedback ahead of the official launch next year. I can't wait to hear from you!

###### **P.S - The Elephant in the Room**
Spoiler alert: I built SportKeeper as a Rock Gym Pro alternative. In fact some parts of our software was designed around making your transition from Rock Gym Pro to Sport Keeper seamless. Features like supporting A.C.H. recurring billing, digital waivers, and staff time sheets are just few examples. My goal is to enable you to move to SportKeeper without any interruption to your business operations.

In order to do that, we have to finish writing the scripts to migrate all that data. This is the hardest part of this entire endeavor. Writing the software was the easy part. Writing scripts to migrate from a separate system with a different database design, that's a story that doesn't have an ending quite yet.

Rock Gym Pro users, stay tuned for more.

[^1]: Update as of January 2021: Stripe Terminal is no longer in beta in the U.S. and is also now available in Canada. See [Stripe's Terminal](https://stripe.com/terminal) Page for you country to see its current status in your country.