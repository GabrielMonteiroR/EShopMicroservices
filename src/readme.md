###### Vertical Slice Architecture
A Vertical Slice Architecture is a software design pattern that organizes code by features or functionalities rather than by technical layers (like controllers, services, repositories, etc.). Each "slice" represents a complete feature or functionality of the application, encapsulating all the necessary components (UI, business logic, data access) required to implement that feature.

###### CQRS Pattern
Command Query Responsibility Segregation (CQRS) is a design pattern that separates read and write operations into different models. In a CQRS architecture, commands (which change state) are handled separately from queries (which retrieve data). This separation allows for more optimized and scalable systems, as read and write operations can be independently scaled and optimized.

###### Mediator Pattern
The Mediator Pattern is a behavioral design pattern that defines an object (the mediator) that encapsulates how a set of objects interact. Instead of objects communicating directly with each other, they communicate through the mediator, which promotes loose coupling and simplifies the interactions between objects.

###### DI (Dependency Injection)
Dependency Injection (DI) is a design pattern used to implement Inversion of Control (IoC) where the control of creating and managing dependencies is transferred from the object itself to an external entity (often a framework or container). This promotes loose coupling and enhances testability by allowing dependencies to be injected at runtime rather than being hard-coded within the class.

###### Minimal API and Routing
Minimal APIs are a feature in ASP.NET Core that allows developers to create lightweight HTTP APIs with minimal configuration and boilerplate code. They enable defining routes and handling requests using simple lambda expressions or methods, making it easier to build small, focused web services.

###### ORM
Object-Relational Mapping (ORM) is a programming technique that allows developers to interact with a relational database using an object-oriented paradigm. ORMs provide a way to map database tables to classes and rows to objects, enabling developers to work with data in a more intuitive and abstract manner without writing raw SQL queries.

###### NUGET packages
- MediatR for CQRS: MediatR is a popular library that implements the Mediator pattern and facilitates the CQRS pattern by allowing you to define commands and queries as separate request/response types.
- Carter for API Endpoints: Carter is a library that simplifies the creation of HTTP APIs in ASP.NET Core by providing a lightweight framework for defining routes and handling requests.
- Marten for PostgreSQL Interaction: Marten is an open-source library that provides a document database and event store built on top of PostgreSQL, allowing for easy interaction with PostgreSQL databases using a .NET-friendly API.
- Mapster for Object Mapping: Mapster is a high-performance object mapping library that allows for easy transformation of objects from one type to another, often used for mapping between domain models and DTOs.
- FluentValidation for Input Validation: FluentValidation is a popular library for building strongly-typed validation rules for .NET applications, allowing for clean and maintainable validation logic.