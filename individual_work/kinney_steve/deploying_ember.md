# Deploying Ember

## Abstract

So, you're sold on using Ember to build an awesome front-end for your ambitious web application—congratulations! Now, what are you going to do on the the server-side? We'll talk about some best practices in setting up your server-side API to play nicely with Ember Data as well as how to use HTTP mocks and server proxying to integrate with `ember-cli`. Lastly, we'll cover the build process as well as popular deployment strategies.

## Details

Ultimately, the outcome is two-fold: for back-end developers to feel comfortable that they'll be able to deploy an Ember application and to help front-end developers with some server-side experience see how easy it is to build a simple back-end to support their ambitious web applications.

The outline would include a synopsis of what Ember Data's REST Adapter is looking for in an API, modifying the adapter when needed, some of the finer points of proxying from `ember-cli` to a server, and setting up HTTP mocks in development for endpoints that are still being built on the server side.

We'll also look at some of the finer points of deploying to Heroku as well as to a VPS as well as some best practices for build processes.

## Pitch

`ember-cli` has done a lot to improve the Ember development story. Many server-side developers who were skeptical about using integrating Ember into their mature workflows have been impressed by how well `ember-cli` takes the misery out of the build process. But in my experience, there a lot of aspiring Ember developers who are really excited about using the framework, but just can't wrap their head about how they would get it up and into production. A lot of this anxiety is unfounded as `ember-cli` and popular back-end frameworks (e.g. Rails, CouchDB, Express) work incredibly well together.