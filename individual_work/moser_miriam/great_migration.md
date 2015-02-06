# THE GREAT MIGRATION

## Abstract (600 words)

We've all generated Rails migrations. Add a table here, rename a column there. But how do migrations actually work?
What’s going on behind the scenes? How do you fix things when they go wrong? Let's take an in-depth look to understand how Rails tracks which migrations need to be run, what you can, can't and shouldn't do in migrations. And, of course, what do you do when things go wrong?

## Details

The typical Rails developer doesn't spend much time thinking about their database. ActiveRecord makes our lives easier, but that doesn't mean we should be scared to poke around. As projects mature most devs keep a massive pile of unnecessary migrations, even when they have gotten out of hand, take too long to run, or don't even setup the database properly. 

It's easy to take migrations for granted. In this session we'll pick them apart:

1. The world before migrations
2. Timestamps and "schema_migrations"
3. The migrations DSL, focusing on change, up, and down
4. Migrations are just Ruby. Very dangerous Ruby.
5. Should a migration ever modify data?
6. Considering scalability when writing migrations
7. Major versions, schema.rb, and creating a roll-up migration
8. The public and hidden Rake tasks you should know about

In the end attendees will have a better understanding of how migrations work and a bag of tricks for doing more than your typical add table / add column.

## Pitch

As a new Rails developer I initially struggled to understand just what migrations were all about and how they worked. This session is the fruit of that research. Our apps are only as good as their data, so developing a deeper understanding of how that data is controlled and shaped will surely pay dividends down the road.
