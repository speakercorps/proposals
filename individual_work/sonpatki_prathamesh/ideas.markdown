## Conference Talk Ideas

### What if ActiveRecord can't do it?

ActiveRecord is awesome. But it doesn't support combining queries
using "UNION", "INTERSECT", "EXCEPT". In our project, we had a
requirement of filtering data based on multiple criteria. Each criterion
was a query in itself. The criteria had to be combined using "and" /
"or" / "but not" like English DSL. ActiveRecord does not support this
out of the box. Doing things in Ruby after getting results of multiple
queries is heavy. First you do multiple queries then you use Ruby
to do UNION/INTERSECTION/EXCEPT.

If ActiveRecord can't do it, go down the Arel way?

Using underlying Arel classes we can build lot of complex queries to
suit our needs. Understanding Arel better will help in understanding
ActiveRecord better.

Thoughts :
How can we add this to ActiveRecord itself?
