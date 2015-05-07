# Building an API with Ruby on Rails

## Abstract

Rails excels at building robust APIs for powering native mobile and client-side web applications—some of which have strong opinions on how they plan on interacting with that API. In this session, we'll discuss how to design an API for your data and—more importantly—how to test our API to make sure it behaves the way we expect it to.

## Details

We'll talk about some standard design patterns for building an API, with an emphasis on JSON API. We'll build a simple note-taking application with two models: notes and tags.

Once we've settled on what our API should look like, we'll write tests for the API to make sure that when the client-side application is built, we can feel confident that our API will rise to the challenge to meet its needs.

Lastly, we'll look at some approaches to build the API itself (ActiveModel Serializers, JBuilder, `.to_json`) to make our tests pass.

## Pitch

We predominately teach Ruby on Rails in our developer training program, but in the last section we also build a project using Ember.js and Ember Data, the latter of which has some really strong default opinions about what it's expecting from an API.

That said Ember Data or any of the other frameworks don't just willy-nilly pick what endpoints they talk to and then hide that information in a black box. They typically have some kind of standard. Too often I've seen developers try to reverse engineer an API to fit their application. I'd like to implore them to consider doing it the other way around.

If you've got a lot of spare time on your hands, you can get away without testing a traditional Rails application (albeit it will involve a lot of time spent clicking around). Doing that is much harder when you're writing an API.