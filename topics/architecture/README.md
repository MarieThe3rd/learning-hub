# 🏛️ Architecture

Master software architecture patterns, system design, Domain-Driven Design, and microservices.

## 🎯 Learning Goals

- [ ] Understand and apply Clean Architecture and Hexagonal Architecture
- [ ] Design systems using CQRS and Event Sourcing patterns
- [ ] Apply Domain-Driven Design (DDD) concepts: bounded contexts, aggregates, domain events
- [ ] Design and evaluate microservices vs. modular monolith trade-offs
- [ ] Design scalable, reliable, and maintainable systems
- [ ] Apply API design best practices (REST, versioning, contracts)
- [ ] Understand messaging and event-driven integration patterns
- [ ] Read and create architecture decision records (ADRs)

## 🗺️ Learning Path

### Stage 1: Architectural Foundations
- Why architecture matters — technical debt and maintainability
- Layered architecture (N-tier) and its limitations
- Separation of concerns and dependency direction
- The dependency rule — high-level policies vs. low-level details

### Stage 2: Clean Architecture
- Layers: Domain, Application, Infrastructure, Presentation
- Dependency inversion at the architectural level
- Ports & Adapters (Hexagonal Architecture)
- Implementing Clean Architecture in .NET

### Stage 3: Domain-Driven Design
- Strategic DDD: bounded contexts, context maps, ubiquitous language
- Tactical DDD: entities, value objects, aggregates, repositories
- Domain events and eventual consistency
- When to use DDD (and when not to)

### Stage 4: CQRS & Event Sourcing
- Command Query Responsibility Segregation fundamentals
- Read models and projections
- Event Sourcing — storing state as a sequence of events
- MediatR pattern in .NET (for CQRS)

### Stage 5: Distributed Systems & Microservices
- Microservices vs. modular monolith — making the right choice
- Service communication: synchronous (HTTP/gRPC) vs. asynchronous (messaging)
- Saga pattern for distributed transactions
- Resilience: retries, circuit breakers, timeouts
- Observability in distributed systems

## 📁 Folder Structure

```
topics/architecture/
├── notes/       ← Add your markdown notes here
├── exercises/   ← Design exercises and architecture diagrams
└── README.md    ← This file
```

## 🔗 Related Topics

- **Dev Principles & Practices** — SOLID and Clean Code are prerequisites for architecture
- **.NET Development** — Implementing architectural patterns in C#
- **Azure Development** — Cloud architecture and distributed system patterns

## 🤖 Mentor

Use the `@architecture-mentor` prompt for architecture-specific guidance, or `@mentor` with `topic = "Architecture"`.
