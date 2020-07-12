This note contains materials from "Patterns, Principles, and Practices of Domain-Driven Design" by Scott Millett and Nick Tune, which is undoubtedly one of the best DDD book out there. You can purchase it from [this link](https://www.amazon.com.au/Patterns-Principles-Practices-Domain-driven-Design/dp/1118714709).

# Domain-Driven Design with TypeScript

## Aggregates

Aggregate is a consistency boundary which decomposes large models into smaller cluster of domain objects that are technically easier to manage.

Designing relationships is between Domain objects is equally important as designing the Domain objects themselves. Relationships that can be traversed in more than one direction also increases complexity. 

**Do not mirror real life or, even worse, the underlying data model when designing the associations/relationships between Domain Objects. Try to justify the relationship only to support domain invariants.**

_**Favor a single traversal direction.**_



