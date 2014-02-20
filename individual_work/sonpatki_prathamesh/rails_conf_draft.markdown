### Title

ActiveRecord can't do it? Keep calm and Do Arel

### Abstract

_What is your talk about? (500 characters or less)_

Active Record is awesome. It covers most of the cases for accessing
database. Active Record handles all this complexity under the hood by making use
of Arel for SQL generation. Most of the times, Rails developers don't have
to know about how Arel works.

Only sometimes Active Record can't satisfy our needs. No need to
worry! Arel can do lot more than what is exposed through Active
Record. So keep calm and ride on Arel.

### Details

_Only visible by review committee._
_Explain the theme and flow of your talk. What are the intended audience takeaways?_
_Include any pertinent details such as outlines, outcomes or intended audience._

This talk will introduce beginning Rails developers to the internals
of Arel and how Arel can be used effectively for generating complex
queries. It will cover the use cases for using Arel and  features of
Arel that are not supported in Active Record out of the box. I will
walk through the code containing complex handcrafted SQL and its Arel
alternatives. Using internals of Arel, will also make
understanding of how Active Record works better.

The intended audience for this talk are beginning Rails developers.

### Pitch

_Only visible by review committee._
_Why is this talk pertinent? What is your involvement in the topic?_
_Explain why this talk should be considered and what makes you qualified to speak on the topic._

Active Record hides Arel from us and does a good job at it. Most of
the Rails developers consider Arel as something that works under the
hood. But we need Arel's features to build complex predicates, joins or need to
combine sub-queries in all possible ways.

This talk presents the idea that if Active Record can't satisfy your
needs, then check Arel before switching to other ORM. You don't need
to start using Arel from day one. But knowing its capabilities will
help when you actually need it. This talk will also help understand
workings of Active Record better.

In our project, we had a feature of filtering data based on multiple
conditions. Each condition was a sub-query in itself. Using Arel, we
were able to combine all the sub-queries in all possible ways. We also
used Arel to build complex predicates. This talk is result of my work
with Arel in our project.

I have given talks at local Ruby meetups. I also help organizing local Ruby meetup.

### Tags

Novice

### Bio

_For the event program (300 characters or less)._
_This information will be hidden from the review committee._

[Prathamesh](https://github.com/prathamesh-sonpatki) writes mostly Ruby on Rails for his day job.
In his personal time he likes to contribute to
[Rails](http://contributors.rubyonrails.org/contributors/prathamesh-sonpatki/commits),
learn new things, play with Emacs. He loves open source software and Ruby.
He also helps organizing local Ruby meetup and maintains local [RUG website](http://www.punerb.org).
