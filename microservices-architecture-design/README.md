
# Microservices Architecture Design

A microservices architecture consists of a collection of small, autonomous services. Each service is self-contained and should implement a single business capability within a bounded context. A bounded context is a natural division within a business and provides an explicit boundary within which a domain model exists.

## What are Microservices?

- Microservices are small, independent, and loosely coupled. A single small team of developers can write and maintain a service.
- Each service is a separate codebase, which can be managed by a small development team.
- Services can be deployed independently. A team can update an existing service without rebuilding and redeploying the entire application.
- Services are responsible for persisting their own data or external state. This differs from the traditional model, where a separate data layer handles data persistence.
- Services communicate with each other by using well-defined APIs. Internal implementation details of each service are hidden from other services.
- Supports polyglot programming. For example, services don't need to share the same technology stack, libraries, or frameworks.


![](images/microservices-logical.png)


## Benefits

- Agility
- Small focussed teams Ex: 5-9 people team to build, test and deploy a feature.
- Small code base
- free to choose any technology for a service
- fault isolation
- scalability
- data isolation

## Challenges

- Complexity
- lack of governance
- network congestion and latency
- data integrity
- management
- versioning



## Acknowledgements

 - [Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/)

