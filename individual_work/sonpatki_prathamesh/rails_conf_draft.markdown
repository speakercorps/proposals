### Title

ActiveRecord can't? Arel can.

### Abstract

_What is your talk about? (500 characters or less)_

ActiveRecord covers the most common cases for accessing the
database. But how does ActiveRecord handle generating complex SQL queries? 

Under the hood it's handled by Arel. Most of the time, Rails developers don't have to know about how Arel works. But Arel has many strengths not exposed through ActiveRecord. 

Let's experiment with Arel directly and wield great SQL power.

### Details

_Only visible by review committee._
_Explain the theme and flow of your talk. What are the intended audience takeaways?_
_Include any pertinent details such as outlines, outcomes or intended audience._

This talk will introduce novice Rails developers to the internals
of Arel and how Arel can be used effectively for generating complex
queries. I will
walk through the code containing complex handcrafted SQL and its Arel
alternatives. 

By the end of the session, attendees will be prepared to use Arel beyond ActiveRecord and have a better understanding of how ActiveRecord works.

### Pitch

_Only visible by review committee._
_Why is this talk pertinent? What is your involvement in the topic?_
_Explain why this talk should be considered and what makes you qualified to speak on the topic._

**FEEDBACK**: I think this misses the mark. What you have here is mostly a restatement of the above. What they're really looking for is an explanation of why *you* are the person to give this talk.

ActiveRecord hides Arel from us and does a good job at it. Most of
the Rails developers consider Arel as something that works under the
hood. But we need Arel's features to build complex predicates, joins or need to
combine sub-queries in all possible ways.

This talk presents the idea that if ActiveRecord can't satisfy your
needs, then check Arel before switching to other ORM. You don't need
to start using Arel from day one. But knowing its capabilities will
help when you actually need it. This talk will also help understand
workings of ActiveRecord better.

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
learn new things, and play with Emacs. He loves open source software and Ruby.
He also helps organize the [Pune Ruby meetup](http://www.punerb.org).
