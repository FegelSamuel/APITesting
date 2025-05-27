# GraphQL
## What is GraphQL?
GraphQL is a query language for APIs. Instead of multiple endpoints like REST (one endpoint for each CRUD method, for example), there is only a singular endpoint. It also allows for dynamic queries (where REST returns a fixed data structure).
## Operation Types
**Query**: Retrieve Data
**Mutation**: Modify Data
**Subscription**: Real-time data updates.
## Best Practices
* Use descriptive names for queries and mutations
* Optimize query performance with batching and caching. If you fuck this up, you open vulnerabilities.
* Secure the endpoint against common vulnerabilities.
* Much of the security needs to be done on your own.
