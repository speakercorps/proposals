## Ideas:

* Lambdas and beginners: a terrible combination?.
  This talk could focus on how the even though novices can still be confused by
  OO principles, exposure to functional thinking can be beneficial.  Some
  options would include clojure or sticking in ruby with lambdas.

* git post-receive hooks on linux
  In a world without Heroku, how do you achieve 'git push live master' bliss?
  This talk will focus on scalable code deployment techniques.

* Edutainment: finding the right balance between working and reading things
  It's important to ...

* ActiveRecord's tsranges
  Inspired by my blog post:
  http://www.simontaranto.com/2013/12/31/using-postgresql-s-tsrange-range-type-with-rails.html

* How data transforms between the params hash and AR model validations
  Inspired by my blog post:
  http://www.simontaranto.com/2014/01/10/how-activerecord-casts-params-before-validation.html

## Feedback from JC

* Lambdas: What do people already know? Why do they want to know about Lambda? Where might they have encountered them? How are they similar and different than blocks? Stay in Ruby land. Turn this into a proposal.
* Git: My first inclination is "don't love it." I think the topic could be reframed as something like "Deployment without Tooling" and basically take the position that tools like Capistrano are too complicated for too little gain.
* Edutainment: I don't get it.
* ActiveRecord: This is really about PostgreSQL's capability, not AR. I think there have been a few talks about PGSQL and the "features you should be using, but aren't." I'd want to see you watch/research those talks and figure out what's left to be said.
* Params: Generalize this a bit into more like "What is `params`?". Isolate the key points including the fact that it's a method, the type of object it returns, how that object differs from a normal hash, and what you can do with it. Also read/think about http://svs.io/post/38090231306/param-objects-in-rails