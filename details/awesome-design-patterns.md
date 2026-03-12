## Overview

Awesome Design Patterns provides a comprehensive collection of software architecture and design patterns across different paradigms, platforms, and technologies.

## Classic Design Patterns

### Creational Patterns

- **Singleton**: Ensure a class has only one instance
- **Factory Method**: Define interface for creating objects
- **Abstract Factory**: Families of related objects
- **Builder**: Construct complex objects step by step
- **Prototype**: Clone existing objects

### Structural Patterns

- **Adapter**: Make incompatible interfaces work together
- **Bridge**: Separate abstraction from implementation
- **Composite**: Tree structures of objects
- **Decorator**: Add responsibilities to objects dynamically
- **Facade**: Simplified interface to complex subsystem
- **Flyweight**: Share common state between objects
- **Proxy**: Placeholder for another object

### Behavioral Patterns

- **Chain of Responsibility**: Pass requests along chain of handlers
- **Command**: Encapsulate requests as objects
- **Iterator**: Access elements sequentially
- **Mediator**: Reduce coupling between components
- **Memento**: Capture and restore object state
- **Observer**: Subscribe to and receive notifications
- **State**: Alter behavior when internal state changes
- **Strategy**: Define family of algorithms
- **Template Method**: Define algorithm skeleton
- **Visitor**: Separate algorithms from objects

## Microservices Patterns

### Decomposition Patterns

- **Decompose by Business Capability**: Organize services around business functions
- **Decompose by Subdomain**: Domain-driven design approach
- **Strangler Fig**: Incrementally migrate legacy systems

### Communication Patterns

- **API Gateway**: Single entry point for clients
- **Backend for Frontend (BFF)**: Custom backends for different clients
- **Service Mesh**: Infrastructure layer for service-to-service communication
- **Circuit Breaker**: Prevent cascading failures
- **Bulkhead**: Isolate resources to prevent failure spread

### Data Management

- **Database per Service**: Each service owns its database
- **Saga Pattern**: Distributed transactions as sequence of local transactions
- **Event Sourcing**: Store state changes as events
- **CQRS**: Separate read and write models
- **API Composition**: Combine data from multiple services

### Deployment Patterns

- **Multiple Service Instances per Host**: Traditional deployment
- **Service Instance per Host**: Isolation and resource control
- **Service Instance per Container**: Containerized deployment
- **Serverless Deployment**: Functions as a Service
- **Service per VM**: Maximum isolation

### Observability Patterns

- **Log Aggregation**: Centralized logging
- **Distributed Tracing**: Track requests across services
- **Health Check API**: Monitor service health
- **Application Metrics**: Performance monitoring
- **Audit Logging**: Track important events

## Cloud Design Patterns

### Availability Patterns

- **Deployment Stamps**: Deploy multiple independent copies
- **Geodes**: Distribute services globally
- **Health Endpoint Monitoring**: Monitor service health
- **Queue-Based Load Leveling**: Buffer requests with queues
- **Throttling**: Control resource consumption

### Data Management Patterns

- **Cache-Aside**: Lazy load data into cache
- **CQRS**: Command Query Responsibility Segregation
- **Event Sourcing**: Store full audit trail of changes
- **Index Table**: Create indexes over distributed data
- **Materialized View**: Pre-computed views
- **Sharding**: Divide data across multiple databases
- **Static Content Hosting**: Serve static assets from storage

### Design and Implementation

- **Ambassador**: Create helper services for network requests
- **Anti-Corruption Layer**: Isolate different subsystems
- **Backends for Frontends**: Separate backend per client type
- **Bulkhead**: Isolate critical resources
- **Gateway Aggregation**: Aggregate multiple requests
- **Gateway Offloading**: Offload functionality to gateway
- **Gateway Routing**: Route requests to different services
- **Sidecar**: Deploy helper components alongside main application
- **Strangler Fig**: Gradually replace legacy system

### Messaging Patterns

- **Asynchronous Request-Reply**: Non-blocking client-server
- **Claim Check**: Split large messages
- **Choreography**: Decentralized service coordination
- **Competing Consumers**: Multiple consumers process messages
- **Pipes and Filters**: Break down processing into steps
- **Priority Queue**: Process messages by priority
- **Publisher-Subscriber**: Broadcast events to subscribers
- **Queue-Based Load Leveling**: Smooth out traffic spikes
- **Scheduler Agent Supervisor**: Orchestrate distributed actions

### Resiliency Patterns

- **Bulkhead**: Isolate elements to prevent cascade failures
- **Circuit Breaker**: Prevent repeated failures
- **Compensating Transaction**: Undo work of failed distributed transaction
- **Health Endpoint Monitoring**: Check service health
- **Leader Election**: Coordinate distributed tasks
- **Queue-Based Load Leveling**: Use queue as buffer
- **Retry**: Retry failed operations
- **Throttling**: Limit resource consumption

## Serverless Patterns

### Function Patterns

- **Function per Endpoint**: One function per API endpoint
- **Single Purpose Function**: Do one thing well
- **Fat Lambda**: Include all dependencies
- **Read-Heavy Cache**: Optimize for reads

### Integration Patterns

- **Event-Driven**: Functions triggered by events
- **Fan-Out/Fan-In**: Parallel processing with aggregation
- **Orchestration**: Step Functions, Durable Functions
- **Choreography**: Event-driven coordination

### Data Patterns

- **Data Lake**: Centralized storage with functions
- **CQRS with Functions**: Separate read/write functions
- **Stream Processing**: Real-time data processing

## Distributed Systems Patterns

### Consensus and Coordination

- **Leader Election**: Select coordinator among nodes
- **Consensus (Paxos/Raft)**: Agree on shared state
- **Two-Phase Commit**: Distributed transaction protocol
- **Saga**: Long-running distributed transactions

### Scalability Patterns

- **Load Balancing**: Distribute load across instances
- **Partitioning/Sharding**: Divide data horizontally
- **Replication**: Copy data across nodes
- **Caching**: Store frequently accessed data
- **CDN**: Content delivery networks

### Reliability Patterns

- **Retry with Backoff**: Retry failed operations with increasing delay
- **Timeout**: Limit waiting time for operations
- **Circuit Breaker**: Fail fast when service is down
- **Bulkhead**: Isolate failures
- **Rate Limiting**: Prevent resource exhaustion

## Security Patterns

- **Gatekeeper**: Dedicated host protects resources
- **Valet Key**: Provide limited direct access
- **Federated Identity**: Delegate authentication
- **API Key Management**: Secure API access
- **Token-Based Authentication**: JWT, OAuth

## Performance Patterns

- **Lazy Loading**: Load resources on demand
- **Eager Loading**: Preload anticipated resources
- **Batching**: Group operations together
- **Pagination**: Limit result set size
- **Connection Pooling**: Reuse database connections
- **Object Pooling**: Reuse expensive objects

## Anti-Patterns

Common mistakes to avoid:

- **God Object**: Object knowing/doing too much
- **Spaghetti Code**: No structure or organization
- **Golden Hammer**: Using same solution everywhere
- **Premature Optimization**: Optimizing before profiling
- **Cargo Cult Programming**: Copy-paste without understanding
- **Tight Coupling**: High interdependence between components

## Implementation Resources

### By Language

- **Java**: Gang of Four patterns implementation
- **Python**: Pythonic design patterns
- **JavaScript**: Modern JS/TS patterns
- **Go**: Idiomatic Go patterns
- **C#**: .NET design patterns
- **Rust**: Ownership-based patterns

### Pattern Catalogs

- **Microsoft Cloud Patterns**: Azure architecture patterns
- **AWS Prescriptive Guidance**: AWS architecture patterns
- **Google Cloud Architecture**: GCP design patterns
- **Martin Fowler's Catalog**: Enterprise application patterns
- **Microservices.io**: Chris Richardson's microservices patterns

## Learning Resources

- **"Design Patterns: Elements of Reusable Object-Oriented Software"** (Gang of Four)
- **"Enterprise Integration Patterns"** by Gregor Hohpe
- **"Patterns of Enterprise Application Architecture"** by Martin Fowler
- **"Cloud Architecture Patterns"** by Bill Wilder
- **"Microservices Patterns"** by Chris Richardson

## Pricing

Free and open-source repository with extensive pattern documentation and examples.