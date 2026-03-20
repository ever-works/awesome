## Overview

A comprehensive collection of resources and tutorials for designing better database schemas. Covers fundamental concepts, best practices, and advanced techniques for relational and non-relational databases.

## Fundamental Concepts

### Database Normalization

- **First Normal Form (1NF)** - Eliminate repeating groups
- **Second Normal Form (2NF)** - Remove partial dependencies
- **Third Normal Form (3NF)** - Eliminate transitive dependencies
- **BCNF** - Boyce-Codd Normal Form
- **4NF and 5NF** - Advanced normal forms

### Denormalization

- When and why to denormalize
- Read vs write optimization trade-offs
- Materialized views
- Redundant data strategies

## Schema Design Patterns

### Relational Patterns

- One-to-One relationships
- One-to-Many relationships
- Many-to-Many with junction tables
- Hierarchical data (adjacency list, nested sets)
- Temporal data modeling

### NoSQL Patterns

- Document embedding vs referencing
- Bucket pattern
- Computed pattern
- Extended reference pattern
- Subset pattern

## Indexing Strategies

### Index Types

- B-tree indexes (default for most databases)
- Hash indexes for equality lookups
- GiST and GIN indexes (PostgreSQL)
- Full-text search indexes
- Spatial indexes

### Index Design

- Composite indexes
- Covering indexes
- Partial indexes
- Index selectivity
- Index maintenance costs

## Performance Optimization

### Query Optimization

- Execution plan analysis
- Query profiling and tuning
- Avoiding N+1 queries
- Batch operations
- Prepared statements

### Partitioning

- Horizontal partitioning (sharding)
- Vertical partitioning
- Range partitioning
- Hash partitioning
- List partitioning

## Data Integrity

### Constraints

- Primary keys
- Foreign keys
- Unique constraints
- Check constraints
- Not null constraints

### Transactions

- ACID properties
- Isolation levels
- Optimistic vs pessimistic locking
- Deadlock prevention

## Best Practices

- Use appropriate data types
- Consistent naming conventions
- Documentation and comments
- Version control for schema changes
- Migration strategies
- Backup and recovery planning

## Tools and Technologies

### Schema Design Tools

- dbdiagram.io - Online database diagram tool
- Draw.io - Diagram creation
- MySQL Workbench - MySQL design tool
- pgAdmin - PostgreSQL administration

### Migration Tools

- Flyway - Version control for database
- Liquibase - Database schema change management
- Alembic - Python migrations
- Sequelize - Node.js ORM with migrations

## Database-Specific Considerations

- PostgreSQL advanced features
- MySQL/MariaDB optimizations
- MongoDB schema design
- Cassandra data modeling
- Redis data structures

## Pricing

Free and open-source resources and tools.