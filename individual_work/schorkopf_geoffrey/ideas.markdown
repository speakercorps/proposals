### Ideas

#### Validations talk

I've run into so/too many issues with complex validations in my time at BNR. We had to build a complex validation system for a travel itinerary form (are you flying? yes, then do you need a ride from the airport? no, then how are you getting to our office? etc.) I loved the complexity of it all, and feel like it's still fresh in my mind. I've found a few cool ways to tackle complex validations (custom validations, custom form objects) and would love to tackle more. We've run into issues where folks will validate a foreign key, but then the foreign object will be deleted and the foreign key, while "present", is useless. This could be a partially "under the microscope" topic, talking about the Rails under the hood bits like how validations work (though some are pretty simple). Not exactly Pat's C talks, but could be interesting. I can also see a talk on validations being boring if not enlivened by good examples / humor / etc.

#### PubSub talk

My final project for gSchool centered around JavaScript publish / subscribe. Not as fresh in my mind. I could talk about when to use PubSub, the service I used (Faye) where PubSub can be problematic (using Heroku, for instance, having to push a separate server), perhaps security issues with publishing JS/ERB files as templates, PubSub in combination with other JS libraries (like d3), etc. It's been a while since I've touched this, but I found it fascinating, as it _feels_ like Rails doesn't do PubSub very well? I'm not sure, would have to research all and more.

#### Finding a Mentor talk

Throughout my brief developer career, I've found that mentor/mentee relationships are perhaps the most invaluable of all relationships. Finding someone to constantly check your code, check your mindset, especially early on. I could talk about my first mentor in high school, first mentor at Google, first mentor at gSchool, then me transitioning into mentorship roles (while still being mentored at BNR). This talk could be about: 1) how to mentor, 2) how to be a mentor, 3) what to do / not to do, 4) what the role of a mentor can be / should be, 5) why mentoring is valuable for both parties, etc. I feel like this talk doesn't have much "edge", and is pretty flat as is. Any suggestions on how to spice it up?

#### Service-Oriented Design - "What Not to Do" talk
Blithe and I worked on a 4 part app together that had a lot of pitfalls early on. This talk would be about how we overcame them. Main talking points: 1) why splitting up your apps into 4 repositories can be super bad, 2) lack of a continuous integration platform like Travis, 3) lack of a solid and consistent bootstrapping task, so that folks who jump on/off the project can't set up a dev server well, 4) how and how not to get a team to work on several apps at once (I can also talk about the gSchool SOD project here), 5) why lack of tests can kill your apps, and why too many Factory-based feature tests can kill them too.

#### The San Francisco problem - Why Economic/Social Stratification Kills off Aspiring Developers and How to Fix It
I'm just throwing out ideas here; the title is probably better than the talk idea is right now. But I've often thought about this problem. Most of the tech jobs/apprenticships/mentorships are in SF. Most companies don't hire remotely, especially not entry level devs. Most schools are very expensive, and only a few have need-based / situation-based scholarships. Even buying a Mac can be a barrier to entry for underprivledged students. How can we encourage needy, aspiring devs to get more involved? This idea isn't very well thought out, but thought I'd throw it out there, as I know you (Jeff) are very passionate about this topic and might have some ideas.
