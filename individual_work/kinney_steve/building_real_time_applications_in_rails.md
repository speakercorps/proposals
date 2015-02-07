# Building Real Time Applications with Rails

## Abstract

Node.js gets a lot of attention for its predisposition towards building real-time applications that break free from the traditional HTTP request-response cycle. But, did you know that Rails 4 has the ability to stream live data to the client baked right in using native HTML5 server-sent events? In this talk, we'll look at building a real-time application using `ActionController::Live` on the server and the `EventSource` object on the client.

## Details

This is a talk in three acts.

Act One: a brief discussion of some of the alternative approaches using WebSockets and EventMachine to push data over a socket connection.

Act Two: introducing `ActionController::Live` and native HTML Server-Sent Events.

Act Three: a demonstration of how easy it is to integrate Redis and extract our real-time feature into a service.

## Pitch

This talk is pertinent because Rails is being overlooked by developers interested in building real-time applications in favor of other technologies despite the fact that it actually has a fairly sophisticated solution to the problem—not to mention that you get to stay within the comfortable confines of the Rails ecosystem and take advantage of everything it has to offer.

I was a Node developer for a few years before coming back to Rails and I really feel that the tools Rails provides are first-class. I believe that this talk should happen because many developers are completely unaware that Rails has this functionality built in.

I teach Ruby and Rails to aspiring developers and building real-time applications is always one of the topics they're most interested in fascinated by and I suspect the same will be true for the RailsConf audience.