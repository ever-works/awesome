# Awesome SQLAlchemy

**Website:** https://github.com/dahlia/awesome-sqlalchemy#readme  
**Category:** Themed Directories  
**Tags:** Python, Database, ORM

## Overview
Awesome SQLAlchemy is a curated, community-maintained directory of libraries, extensions, utilities, and learning resources built around SQLAlchemy, Python’s SQL toolkit and Object Relational Mapper. The list is inspired by the wider "awesome-*" ecosystem and is licensed under Creative Commons Attribution-ShareAlike 4.0.

## Features

### General
- Curated collection of third‑party tools and resources for SQLAlchemy.
- Organized by topic (e.g., data structures, types, migrations, profiling, GIS, etc.).
- Includes links out to official SQLAlchemy documentation and related ecosystems.
- Openly licensed content (CC BY-SA 4.0) for reuse and adaptation.

### Data Structures
- Versioning and auditing extensions for SQLAlchemy models (e.g., tracking changes to rows over time, audit history).

### Data Types & Utilities
- Support and examples for using standard Python types like `enum.Enum` and `datetime.datetime` with SQLAlchemy.
- Various utility functions, new column types, and helpers that extend SQLAlchemy’s built‑in type system.

### Database Migration Tools
- Section dedicated to tools that handle schema migrations for SQLAlchemy-backed databases (e.g., versioned DDL changes, upgrades/downgrades).

### Dialects
- References to SQLAlchemy’s official dialect documentation for working with different database backends.
- Helps users find dialect-specific configuration and usage notes (e.g., PostgreSQL, MySQL, Oracle, SQL Server, SQLite, etc.).

### Documentation
- Links to documentation resources related to SQLAlchemy and its ecosystem (tutorials, guides, references).

### File and Image Attachments
- Section for libraries that integrate file or image attachment handling with SQLAlchemy models (e.g., storing metadata, paths, or references in the database).

### Forms and Data Validation
- Tools that connect SQLAlchemy models with schema/validation libraries.
- **ColanderAlchemy**:
  - Auto-generates Colander schemas from SQLAlchemy mapped classes.
  - Enables reuse of model definitions as validation schemas.
  - Integrates with Deform for building forms based on these schemas.
  - Reduces duplication between database model definitions and validation schemas.

### Full-text Searching
- Section for libraries that provide full-text search capabilities on top of SQLAlchemy models (e.g., search indexing and querying helpers).

### GIS and Spatial Databases
- **GeoAlchemy**:
  - Provides extensions to work with spatial databases via SQLAlchemy.
  - Supports PostGIS, Spatialite, MySQL, Oracle, and MS SQL Server 2008.
- **GeoAlchemy 2**:
  - Extensions for spatial databases with a focus on PostGIS.
  - Supports PostGIS 1.5 and 2.x.
  - Supports Spatialite with some additional configuration on the application side.
  - Designed to be simpler to use and maintain than the original GeoAlchemy.

### Internationalization
- Internationalization extensions for SQLAlchemy models (e.g., handling translated fields, locale-specific content).

### Profiling and Performance Analysis
- **SQLTap**:
  - Profiles and introspects SQL queries executed via SQLAlchemy.
  - Helps analyze query performance characteristics.
- **nplusone**:
  - Auto-detects N+1 query patterns in applications using SQLAlchemy or other Python ORMs.
  - Identifies unnecessary queries caused by lazy loading or inefficient eager loading.

## Licensing
- Content is available under the Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0).

## Pricing
- Awesome SQLAlchemy is an open, public list. No pricing or paid plans are indicated; usage is free.