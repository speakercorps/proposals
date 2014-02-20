# Tech talks

I feel like I had other tech talk ideas that I put in the speakercorps google form, but I forget them now so I guess I wasn't that excited about them ;)

## Breaking up a monorail

This is mostly what I've been working on at my day job at Think Through Math-- we have a huge rails app that we're slowly breaking apart and rewriting as separate apps that use the monorail as an API. I feel like people have been talking about this a lot lately? Is this overdone? Is what we've done generalizable?

Challenges:

* Current rails app is getting too big for any one person to understand-- has lots of different functionality that is all intertwined (rails doesn't stop you from shooting yourself in the foot in this manner, nor should it necessarily)
* Tests are slow, coverage isn't great -> scared to change
* School year dictates release schedule for big features

Things we've broken out:

* A data warehouse in order to speed up student performance report generation
* A single page app for students doing math problems in backbone/marionette in order to create a responsive, interactive interface (basically a rewrite then extension of our interface in rails)
* A node.js chat application for our teachers to chat with students who need help (this actually used to be flash, not rails per se)

Things we want to break out:

* A content editing application for people authoring the math problems (probably also in backbone/marionette)

Things I think have helped us accomplish this:

* The rollout gem for feature flipping
* Leveraging business desire for new features into political capital for legacy code replacement
* Growing a culture of doing things The Right Way rather than adding another hack on top of a pile of hacks
* Advancements in open source since the app was originally written (both in rails and outside of rails)


## Leprechaun hunting

Inspired by @morendil's Leprechauns in Software Engineering book, let's deconstruct a commonly held tenet of programming/SE/ruby and see where it came from and if it's really true.

Problem: I don't have one in mind yet. Maybe "Rails is slow/can't scale"?

## Leprechaun experiments

I envision this as more of a workshop, not sure where this would be appropriate. Again inspired by @morendil's book which shows that not very many actual controlled experiments have been done where the data is publicly available, let's do a science!

When I was in the middle of the book, I wanted to do something like testing if 10x programmers exist (hook to get people to attend/participate: "Think you're a 10x programmer? Think 10x programmers don't exist? Prove it!"). Give everyone a task (see below), let them solve it however they like (but document their approach-- ie pairing vs not, TDD vs no tests, etc) and somehow quantify results. Publish results & code (anonymous/use an ID # instead of your name) for anyone to analyze/critique/build on (and I'd write up my analysis afterward too).

Task ideas:

* A puzzlenode problem, i think people have done those less than katas
* The legacy code retreat codebase, task is to find and fix bugs, score is bugs found + bugs fixed, interesting wrinkle is discussing what a bug is

BUT at the end of the book, @morendil advocates treating programming as more of a sociology problem rather than a science problem, and doing experiments like that. I have an interest in behavioral economics but no real experience designing experiments like those, but I think that would be fun.

## Writing the code you wish you had

A TDD/design technique that I love using that maybe doesn't come naturally -- inspired by this blog post which describes what I like doing but seems like some people found it to be revelatory? http://patshaughnessy.net/2014/2/10/use-an-ask-dont-tell-policy-with-ruby

I've seen my coworkers/colleagues struggle to get going with TDD-- like once you write the test "this object should exist", have it fail, create the object, have it pass... what do you do next? I start pretending my object can do things that I have no idea how to make it do yet.

# "Soft" talks

## How to be a better open source maintainer

* Sharing my experiences maintaining rstat.us-- both what I did right and what I did wrong
* In a positive way aimed at current maintainers who want to get better or people who may want to be maintainers (the poor souls), not saying that anyone sucks

### Background (will look up exact facts if this looks promising):

* Steve gave me the keys to rstat.us on x date
* We have had a lot of contributors https://rstat.us/about (increased from y to z while i was maintaining?)
* For N people, this was their first open source contribution (I think I might be able to find this out, I have a few anecdotes if not)

### Things I learned

* Be nice no matter what - use emoji on every pull request, because who can be mean using emoji?
* Acknowledge pull requests/issues filed even if you don't have time to do anything with them right away (ex: ukraine revolution). Don't let PRs languish (which I am totally doing right now, oops)
* For someone's first PR, accept & make any necessary modifications yourself, explain why you changed what you did on the PR (rather than rejecting or requesting they make the modifications). For their next PR, then ask them to do it. Gradual teaching and expectation raising, limit friction for getting 1st PR in.
* Give someone push access when you accept their first PR (like rubinius). Have policy that no one pushes their own stuff, but now you have more PR review help! Not saying deploy permissions-- they can't really hurt anything with push permissions (see jenkins incident)
* Have well-defined small issues marked as such for people who want to help but aren't sure how
* Fade away before you burn out (aka appoint another maintainer, oops)

# Places I'm most interested in submitting

* Railsconf if I get my act together in time
* Windy City Rails
* Burlington Ruby
* Nickel City Ruby