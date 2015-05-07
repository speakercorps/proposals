# Lessons Learned Teaching Ember

## Abstract
One of the most important factors in the success of an open source project is its ability to build a community—and a big part of building a community is getting new developers acclimated. In this session, we'll talk about some of the common pitfalls and misconceptions held by newcomers to Ember, which areas tend to cause the most confusion, and what we can do about it in order to become a stronger and more diverse community.

## Details
In this talk, I'd like to cover some of my experiences working with relatively new developers who are also completely new to Ember. What preconceived notions do they have coming into Ember? Of those notions, which are accurate and which are not? What are some of the common conceptual challenges that students face when tackling their first Ember application? What are some of the immediate first questions that they have? Which ones do we have good answers for? Which ones do we not?

The intended audience is split between more experience Ember developers who are in the position of mentoring newer developers as well as the newer developers themselves to give them a sense of the community resources available.

I polled our students who have just spent the last month learning Ember in order to get an authentic sense of the struggles and misconceptions they had learning Ember:

Far and away, the biggest common thread was misunderstandings in regards to the distinction between what MVC means in most server-side frameworks and what it means in client-side frameworks, like Ember. They struggled with the role of the controller as well as how and when to use web components. If some kind of functionality can be isolated away from other routes, controllers, and views, it's a good candidate to be a component.

Web developers with a lot of server-side experience have a hard time wrapping their heads around the idea that they can have multiple routes and that controller are long-lived and can communicated with each other when they need to. They also struggled with integrating third-party and native browser functionality (e.g. geolocation or WebSockets) without just ignoring Ember's MVC and patching into the global object.

Students struggled with controller and view scoping and the idea that the controller decorates the model. They had a hard time getting their collective heads around the idea that that if you called this.get('age') in the controller that it proxied to the model. In the same vain, they struggled with the idea that {{each}} in the template was also implicitly meaningful. (I understand that this is being taken out in Ember 2.0.)

Students had difficulty with the idea that routes, controllers, views, and templates were generated on the fly in the absence of a defined class. They also had a hard time with the idea of nested routes. One of our students said, "It was definitely a shift to see the router as the center of the application as opposed to an afterthought that you implemented just to make it work."

They also had a hard time understanding the role of the Ember Resolver. One student commented, "it took me some time to understand that I had to put my files in places that meant something to the Ember Resolver, not where I thought they should go."

With all of this said, there was a common refrain: it's can be somewhat difficult to learn Ember because of the lack of up to date resources. ember-cli is clearly the future, but the official documentation doesn't refer to it yet. But more importantly, it's on us as a community to make it a point to publish great content to make it easier to find solution to common problems.

So, there is a lot of content (and there will probably be more as we work with 40 more students between now and March). I'm imagining that the 30 minute narrative will go something like this:

* A quick overview of some of the areas where students struggle
* Touch on some of the really great things the community has done over the last year (e.g. Ember Addons, Built with Ember, live-streaming local meet-ups)
* Some areas where we can improve (e.g. example applications and reference implementations of common features like using OAuth in an Ember application, updating documentation to support ember-cli and Ember 2.0)
* A call to action for the community to document best practices
* I'd like to end call to action to all developers who really care about the Ember community—which I hope is most of the audience—to publish everything they know and build a canon of resources on how to best use Ember to create really wonderful web applications.

## Pitch

For the last six months or so, I've been teaching Ember.js to budding developers at a developer bootcamp—for lack of a better term. Over the course of the first seven months, students learn Ruby, Sinatra, Rails, and JavaScript. In the final module, we introduce them to Ember. I've had the good fortune of being able to observe dozens of students go through the process of learning Ember. Some concepts instantly click and others cause confusion.

It's important to bring in new developers from a diverse range of backgrounds and get them up to speed on the features of the framework as well as the values of its community. Not just how the framework works, but why it works like it does and the considerations that went into making those design decisions.

How can we—as the Ember—community take the experiences of new developers and use them to inform improve the on-boarding process and thus build a strong collective?