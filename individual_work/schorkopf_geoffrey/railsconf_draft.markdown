### Title

Valid Point, My Friend! - A Look at Complex Rails Validations 

### Abstract

_What is your talk about? (500 characters or less)_

Rails validations are taken for granted. As a budding developer, I found my database littered with half-baked instances, view forms an innavigable jungle, and ActiveRecord models a cluster of "validate this when this but not then this!" mess.

In this session we'll look at the challenges encountered in a real life project. We'll look at how to go beyond the normal built-in validations and build our own. We'll reduce confusion and clutter, producing intelligent form objects and speedy unit tests.

### Details

_Only visible by review committee._
_Explain the theme and flow of your talk. What are the intended audience takeaways?_
_Include any pertinent details such as outlines, outcomes or intended audience._

Geared towards beginning Rails developers, this talk will guide our audience through many tips and tricks I didn't know when I started out. I will focus on building out an intricate travel form, starting from an initial mess to a DRY series of objects. Through our journey, we'll tackle:

* an overview of validations in Rails and why they're critical to your app and database,
* a dive under the hood at how ActiveRecord::Validations works
* how to add custom validators to ActiveRecord::Validations
* tips on test-driving validation/form objects,
* tips for writing fast specs and avoiding integration tests,
* tips on how using Rails validations can create a beautiful user experience

### Pitch

_Only visible by review committee._
_Why is this talk pertinent? What is your involvement in the topic?_
_Explain why this talk should be considered and what makes you qualified to speak on the topic._

Building out an intelligent object like a User or Itinerary or Order, one that requires certain attributes in certain situations to make your app really jive, is not an intuitive process. An experienced developer knows that data integrity issues are one of the most common sources of software bugs. Everything works just fine until users get a hold of it. 

Validating that objects are built the way you expect is core to both the Rails Way and the user's experience. Though these patterns might not be immediately apparent in Rails, splitting out form objects is a technique that beginners can definitely grasp. 

I have used complex validations and form objects in two related Rails applications for our internal team. From this experience, I learned several valuable lessons, techniques for DRYing up code, and new tactics in Rails 4 that have aided me tremendously.

Though new to Rails, I have participated in giving 5-minute didactic "lightning talks" once a month for half a year, which helped sharpen both my soft and technical talk skills, covering topics from specific Ruby gems to the social aspects of technology. Additionally, I have given several talks on open source repositories, pitching both the product/idea and delving into interesting pieces of the codebase.

### Tags

Novice, Real World Rails, Testing

### Bio

_For the event program (300 characters or less)._
_This information will be hidden from the review committee._

Geoffrey is a cruciverbalist, ukulelist, and audiophile. He is a graduate of the gSchool development program in Denver, and currently is a Rails consultant at Big Nerd Ranch in Atlanta. 
