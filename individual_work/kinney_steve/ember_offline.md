# Ember Offline

## Abstract
What happens to your application when there is a poor—or no—Internet connection? Ember makes it easier to build native-like applications. But, many native applications typically still work when they're offline. We'll discuss how you can enable your application to work on the New York City Subway. We'll look at manifests, caching, local storage, and syncing.

## Details
In this talk, we'll look at the evolution of an example note-taking application. In its first form, it won't work offline at all.

Next we'll look at how to implement offline asset caching so that our resources load even when we don't have connection with the server.

Third, we'll look at some strategies for storing information locally, either through LocalStorage or through a library like PouchDB.

Finally, we'll look at how to sync that data back up with our server along with some of the pitfalls that come along with that.

## Pitch
The first thing I thought when I started developing Ember applications was that it very similar to how I would go about building a native application, but—even better—I could deploy and use it on the web. It was a dream come true. It felt like I was developing an application not just moving pieces of the DOM around to create the illusion of an application in the browser. That said, I think the next hurdle comes down to the fact that these Ember-created web applications won't work offline without some fine tuning.