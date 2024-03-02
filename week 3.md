# Week 3 Notes #


## Architectural Structures ##

A set of elements held together by a relation.

Categories:
- **Module:** represents a partitioning of the system into implementation units or modules (eg. database, Business Logic, UI, etc.)
- **Component and Connector:** represent runtime components and communication vehicles among them
- **Allocation:** represents the relationship between the system and the non-software structures in its environment (eg. hardware, development teams, etc)

## Architectural Patterns ##

Establishes relation between a context, a problem, and a solution.

Based on desired attributes:
- Modifiability
- Availability
- Interoperability
- Scalability
- Reusability
- Performance

## Layered Pattern

Software is divided into layers
- Each layer is a grouping of modules that offers a cohesive set of services
- Every piece of software is allocated to exactly one layer
- Closed architecture: only next=lower-layer uses are allowed
- Open architecture: a layer can use services from any lower layer

Promotes modifiability and reusablility

Challenges:
- Up front cost and complexity
- 

  
