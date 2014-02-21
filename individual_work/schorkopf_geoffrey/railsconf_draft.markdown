### Title

Valid Point, My Friend! - A Look at Complex Rails Validations 

### Abstract

_What is your talk about? (500 characters or less)_

Rails validations are often taken for granted or afterthoughts in our codebase, but should be considered on every new model or migration.

Though mostly technical, I will also cover the real life mistakes I made creating my company's course registration platform, braving confusion and clutter to produce intelligent form objects and speedy unit tests.

We'll cover building out complex validations, how ActiveRecord::Validations works, and how to test drive your validations.

### Details

_Only visible by review committee._
_Explain the theme and flow of your talk. What are the intended audience takeaways?_
_Include any pertinent details such as outlines, outcomes or intended audience._

Geared towards beginning Rails Developer, this talk will guide our audience through many tips and tricks I didn't know when I started out. I will focus on building out a complex travel form, starting from an initial mess to a DRY series of objects. Through our journey, we'll tackle:

* an overview on validations in Rails, and why they're critical to your app and database,
* tips on DRY test-driven development of validation/form objects,
* tips for writing fast specs and avoiding integration tests,
* how to add custom validators to ActiveRecord::Validations, coupled with:
* a dive under the hood at how ActiveRecord::Validations works,
* tips on using Rails validations can create a beautiful user experience

### Pitch

_Only visible by review committee._
_Why is this talk pertinent? What is your involvement in the topic?_
_Explain why this talk should be considered and what makes you qualified to speak on the topic._

Building out an intelligent object like a User or Itinerary or Order, one that requires certain attributes in certain situations to make your app really jive, is not an intuitive process. As a budding developer, I found my database littered with half-baked instances, my view forms an innavigable jungle, my ActiveRecord models a cluster of "validate this, when this, but not when this!" mess.

However, validating that these objects are built the way you expect is core to both the Rails Way and the user's experience. Though these patterns might not be immediately apparent in Rails, splitting out form objects is a technique that beginners can definitely grasp. I think it's critical to share my personal pitfalls and arm beginners with this knowledge.

I have used complex validations and form objects in two related Rails applications for our internal team. From this experience, I learned several valuable lessons, techniques for DRYing up code, and new tactics in Rails 4 that have aided me tremendously.

Though new to Rails, I have participated in giving 5-minute didactic "lightning talks" once a month, which helped sharpen both my soft and technical talk skills, covering topics from specific gems to the social aspects of technology. Additionally, I have given over five talks on open source code bases, pitching both the product/idea and delving into interesting pieces of the codebase.

### Tags

Novice, Real World Rails, Testing

### Bio

_For the event program (300 characters or less)._
_This information will be hidden from the review committee._

Geoffrey is a cruciverbalist, ukulelist, and audiophile. He is a graduate of the gSchool development school in Denver, and currently is a consultant for Ruby on Rails at Big Nerd Ranch in Atlanta. 
