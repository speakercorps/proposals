## Death to the Views

### Proposal

The days of writing ERB view templates and serving up the same HTML to all comers are over. There are now only APIs.

If we model the view layer as an external service, we'll gain:

* Unification of "Normal" and "API" controllers
* Simplification of controller code
* Request specs that don't rely on the DOM
* Adaptability to serving data-only clients, rich JavaScript clients, and all spectrum of browsers

This is not the future, it's what we need right now. And thanks to new work like `ActiveModelSerializer`, it's getting easier. Let's implement a Rails application that delivers the API first.

### Status

* I think this was proposed to GORUCO 2012 and not accepted
