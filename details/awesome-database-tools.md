## Overview

Database tools enhance productivity for developers, DBAs, and data engineers working with relational and NoSQL databases across various platforms.

## Features

### Database GUI Clients

#### Multi-Database
- **DBeaver**: Universal database tool
  - Support for 100+ databases
  - SQL editor with auto-completion
  - ER diagrams and schema browser
  - Data import/export
  - Free (CE) and commercial (EE) versions

- **TablePlus**: Modern native database client
  - Clean interface
  - Multi-tab and multi-window
  - Code review and security
  - macOS, Windows, Linux, iOS

- **Beekeeper Studio**: Open-source SQL editor
  - Tabbed interface
  - Auto-complete
  - Query runner
  - Free and open-source

- **DataGrip**: JetBrains database IDE
  - Intelligent query console
  - Schema navigation
  - Version control integration
  - Subscription-based

#### Specialized Clients
- **pgAdmin**: PostgreSQL management
- **MySQL Workbench**: MySQL design and admin
- **Studio 3T**: MongoDB GUI
- **RedisInsight**: Redis visualization
- **Robo 3T**: MongoDB client

### CLI Tools

#### Query Interfaces
- **usql**: Universal command-line interface for SQL databases
- **pgcli**: PostgreSQL with auto-completion
- **mycli**: MySQL/MariaDB with auto-completion
- **litecli**: SQLite with auto-completion
- **redis-cli**: Redis command-line
- **mongosh**: MongoDB shell

#### Utilities
- **q**: Run SQL on CSV files
- **xsv**: Fast CSV toolkit
- **miller**: CSV/JSON/etc data processing
- **jq**: JSON processor (useful for JSON columns)

### Migration and Version Control

#### Schema Migration Tools
- **Flyway**: Database migration tool
  - Version control for databases
  - Java-based
  - SQL and Java migrations
  - Community and commercial editions

- **Liquibase**: Database schema change management
  - XML, YAML, JSON, SQL formats
  - Rollback support
  - Multiple database support
  - Open-source and commercial

- **golang-migrate**: Go migration library
  - CLI and library
  - Multiple source/database drivers
  - Up/down migrations

- **Atlas**: Modern schema migration
  - Declarative migrations
  - Terraform-like workflow
  - Schema inspection

#### Schema Diff and Sync
- **migra**: PostgreSQL schema diff
- **Skeema**: MySQL/MariaDB schema management
- **SchemaHero**: Kubernetes-native schema migrations

### Data Modeling and Design

#### ER Diagram Tools
- **dbdiagram.io**: Quick database diagrams
- **ERD Editor**: Open-source ERD tool
- **Lucidchart**: Cloud-based diagramming
- **draw.io**: Free diagramming tool
- **MySQL Workbench**: MySQL-focused modeling

#### Schema Documentation
- **SchemaSpy**: Database schema analyzer
- **dbdocs**: Database documentation
- **schemachange**: Snowflake schema change

### Database Performance

#### Query Analysis
- **EXPLAIN analyzers**: Visualize query plans
- **pg_stat_statements**: PostgreSQL query stats
- **pt-query-digest**: MySQL slow query analysis
- **pgBadger**: PostgreSQL log analyzer

#### Monitoring
- **Percona Monitoring and Management**: Database monitoring
- **pgwatch2**: PostgreSQL monitoring
- **Anemometer**: MySQL slow query monitor
- **VictoriaMetrics**: Time-series database for metrics

### Backup and Recovery

#### Backup Tools
- **pg_dump/pg_restore**: PostgreSQL backup
- **mysqldump**: MySQL backup
- **mongodump**: MongoDB backup
- **Barman**: PostgreSQL backup and recovery
- **pgBackRest**: PostgreSQL backup solution
- **mydumper/myloader**: MySQL parallel backup

#### Point-in-Time Recovery
- **WAL-G**: Archival and restoration
- **pitr**: PostgreSQL PITR tool

### Data Import/Export

#### ETL Tools
- **Apache NiFi**: Data integration
- **Airbyte**: EL(T) platform
- **Meltano**: Open-source ELT
- **Pentaho**: Data integration suite

#### CSV/Excel Tools
- **csvsql**: Execute SQL on CSV
- **pgloader**: Data loading tool
- **mysql-import**: MySQL bulk import

### Testing and Development

#### Test Data Generation
- **Faker**: Generate fake data
- **Mockaroo**: Realistic test data
- **generatedata**: Online data generator
- **Databunker**: Privacy-friendly test data

#### Database Seeding
- **Laravel Seeders**: PHP framework seeders
- **Django Fixtures**: Python fixtures
- **Rails Seeds**: Ruby on Rails
- **TypeORM Seeders**: Node.js seeders

### Security and Compliance

#### Access Control
- **Teleport**: Database access proxy
- **StrongDM**: Access management
- **Boundary**: HashiCorp access tool

#### Data Masking
- **PostgreSQL Anonymizer**: Data masking
- **MySQL Enterprise Masking**: Data redaction
- **Delphix**: Data virtualization and masking

#### Audit and Compliance
- **pgAudit**: PostgreSQL audit logging
- **MySQL Enterprise Audit**: MySQL auditing
- **Audit trail**: Various solutions per database

### Development Frameworks

#### ORMs
- **TypeORM**: TypeScript/JavaScript ORM
- **Prisma**: Next-generation ORM
- **SQLAlchemy**: Python ORM
- **Hibernate**: Java ORM
- **ActiveRecord**: Ruby ORM
- **Entity Framework**: .NET ORM

#### Query Builders
- **Knex.js**: SQL query builder for Node.js
- **jOOQ**: Java SQL builder
- **Squirrel**: Go SQL builder

### Cloud and SaaS Tools

#### Database Platforms
- **Supabase**: Open-source Firebase alternative
- **PlanetScale**: Serverless MySQL platform
- **Neon**: Serverless Postgres
- **MongoDB Atlas**: Managed MongoDB
- **Amazon RDS**: Managed relational databases
- **Google Cloud SQL**: Managed SQL databases

#### Database Proxies
- **ProxySQL**: MySQL proxy
- **PgBouncer**: PostgreSQL connection pooler
- **Heimdall**: SQL proxy

## Use Cases

- Database schema design and modeling
- SQL query development and optimization
- Database migration and version control
- Performance monitoring and tuning
- Data import/export and ETL
- Database backup and disaster recovery
- Test data generation
- Multi-database management

## Pricing

Ranges from free open-source tools to enterprise commercial solutions:
- **Free/Open-Source**: DBeaver CE, Beekeeper Studio, pgcli, Flyway Community
- **Freemium**: TablePlus, dbdiagram.io
- **Subscription**: DataGrip ($89/year), DBeaver EE, Flyway Teams
- **Enterprise**: Percona PMM, Liquibase Pro (custom pricing)