## Conference Talk Ideas

### The Internationalization Talk

I was recently asked to build an internationalized/ localized app for a client. Not only did the content of the site need to be in multiple languages, the user-supplied info also needed to be stored in the database in multiple languages. I discovered a few gems and techniques that helped me solve some of the problems I encountered while building this app. The story of this journey (and some of the pitfalls I encountered along the way) might be beneficial to other developers, particularly beginners that might not have ever used i18n or built an app in more than one language.

#### Feedback

* JC: I gave an Internationalization talk a few years ago. I felt that it was a solid talk, but i18n is hard to make interesting. I18n is one of those things people know they'll need to do one day, but few actually do it. How can you put an "edge" on it? How do you make people care?

* KO: Jeff's talk can be seen here: [Internationalization and Localization](http://www.confreaks.com/videos/1136-scrc2012-internationalization-and-localization)

* KO: There are two other I18n talks that I really like too, which could give you ideas for things that can give it an edge: [Linguistic Potluck](http://www.confreaks.com/videos/1110-gogaruco2012-linguistic-potluck-crowdsourcing-localization-in-rails) by Heather Rivers and [Cultured Localization: How not to offend 1 billion people](http://www.confreaks.com/videos/2111-arrrrcamp2012-cultured-localisation-or-how-not-to-offend-1-billion-people) by Ryan Stenhouse.

* BER: I'm not sure the best way for me to give it some "edge". Maybe one way is to focus the talk towards the "Novice" track for RailsConf. I can definitely emphasize how internationalizing an app from the begining is going to make things a lot easier in the long run. It's also super helpful when writing tests and it keeps the views a lot cleaner. Particularly for beginners, they might not know that they should be doing it even for single-language apps. I definitely don't want to verge into the "What You’re Doing is Dumb" genre though.

* BER: I've actually watched Jeff's talk a couple of times, once before I'd ever built a Rails app from scratch and then after I finished the app that I built for this talk idea. It's amazing how different my level of understanding was each time. It'd be interesting (to me) to see a similar version of Jeff's talk targeted for an audience of Novices.

* BER: The linguistics aspect of internationalization is interesting but for sure outside of my comfort zone. All of my translations were provided by the client and I avoided using a lot of tokens. We didn't use [Locale](http://www.localeapp.com) but that would have been helpful at least for the static text in the app. Issues that can arise from the translation aspect are for sure something I would mention in the talk but I'm not sure it should be the main focus for me. 


### The SOA Talk

I recently worked on a SOA that had several connected Rails apps and used ActiveResource. There were definitely some pain points with this architecture and the general workflow between several developers. I feel less strongly about this talk idea but it might be interesting to talk about some of those pains and ways that we did/ could have solved them.

### The Former Scientist Talk

Maybe I could talk about how my background as a scientist affects the way I write code/ solve problems when developing. I definitely see some parallels between the scientific method and troubleshooting a bug. For instance, you start with some feedback from the app like an error message. You make a hypothesis about what's wrong. You come up with a plan/procedure on how to fix it. You make the changes and get some data in return. Your hypothesis is confirmed and you've fixed the bug or it's still broken and you start a new "experiment." There are also connections between 1) keeping a good lab notebook and updating documentation and  2) researching by reading papers/ literature and using online resources like Rails docs, Stack Overflow, etc. 