### Ideas

#### Validations talk

I've run into so/too many issues with complex validations in my time at BNR. We had to build a complex validation system for a travel itinerary form (are you flying? yes, then do you need a ride from the airport? no, then how are you getting to our office? etc.) I loved the complexity of it all, and feel like it's still fresh in my mind. I've found a few cool ways to tackle complex validations (custom validations, custom form objects) and would love to tackle more. We've run into issues where folks will validate a foreign key, but then the foreign object will be deleted and the foreign key, while "present", is useless. This could be a partially "under the microscope" topic, talking about the Rails under the hood bits like how validations work (though some are pretty simple). Not exactly Pat's C talks, but could be interesting. I can also see a talk on validations being boring if not enlivened by good examples / humor / etc.

#### PubSub talk

My final project for gSchool centered around JavaScript publish / subscribe. Not as fresh in my mind. I could talk about when to use PubSub, the service I used (Faye) where PubSub can be problematic (using Heroku, for instance, having to push a separate server), perhaps security issues with publishing JS/ERB files as templates, PubSub in combination with other JS libraries (like d3), etc. It's been a while since I've touched this, but I found it fascinating, as it _feels_ like Rails doesn't do PubSub very well? I'm not sure, would have to research all and more.
