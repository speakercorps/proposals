# Building Real-Time Applications in Ember

## Abstract

In this session, we'll investigate a few strategies for integrating browser features like WebSockets as well as third-party libraries into our ember-cli applications. We'll look at how to structure an application using standalone controllers, initializer objects, and services. Our example application will be a real-time chat application that uses WebSockets to push notification to connect clients. We'll build the application with native WebSockets and talk about how to leverage external libraries like Socket.io and Faye.

## Details
The intended audience is intermediate Ember developers who are comfortable using ember-cli to structure their applications, but are having some difficulties incorporating non-Ember functionality into this structure.

The structure of the talk will be:

* a brief introduction to WebSockets and how their typically implemented (i.e. selector-based development);
* why that doesn't work when you're building ambitious web applications;
* implementing WebSockets with a standalone controller;
* a discussion about Services in Ember and how to access them;
* and using Services today in ember-cli with objects and initializers

## Pitch
As the Ember community moves from declaring properties on a global object to more structured applications using ember-cli it can get a little confusing to figure out how to integrate non-Ember libraries and browser features. In part, this is a talk on using WebSockets in an Ember project, but it's also a talk on how to bring in a wide range of functionality into your application.

I gave this talk at a local meet-up recently and it was their most well-attended meet-up to date (that said, it's never been done at a conference or anything like that). The talk was also well received, which leads me to believe that it will be useful for a wider Ember-centric audience as well.