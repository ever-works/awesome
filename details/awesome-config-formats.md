## Overview

Awesome Config Formats is a curated list of awesome configuration formats and their respective libraries and specifications. This list covers various data serialization and configuration languages used in modern software development.

## Popular Configuration Formats

### YAML
Human-friendly data serialization standard with:
- Support for complex data structures
- Reference and anchoring capabilities
- Multi-line strings
- Widely used in Docker, Kubernetes, Ansible

### TOML
Minimal configuration file format:
- Easy to read due to obvious semantics
- Maps unambiguously to hash tables
- Designed for config files
- Used by Rust's Cargo, Python's Poetry

### JSON
Universal data interchange format:
- Simple and widely supported
- Native JavaScript support
- Strict syntax
- Used everywhere

### HCL (HashiCorp Configuration Language)
Structured configuration language:
- Human and machine friendly
- Used by Terraform, Vault, Nomad
- Supports interpolation and functions
- JSON-compatible

## Alternative Formats

- **HanSON** - JSON for Humans with unquoted identifiers and comments
- **HOCON** - Human-Optimized Config Object Notation
- **INI** - Simple key-value configuration format
- **XML** - Extensible markup language for configuration

## Tools

- **dasel** - Query and update data structures using selectors from the command line
  - Supports JSON, YAML, TOML, XML
  - Zero runtime dependencies
  - Unix-friendly

## Comparison Criteria

- Human readability
- Machine parseability
- Feature richness (comments, references, types)
- Tool ecosystem
- Performance
- Error handling

## Use Cases

- Application configuration
- Infrastructure as Code
- CI/CD pipelines
- Container orchestration
- API specifications
- Build systems