## Overview

Network automation is a cross between the discipline of network infrastructure and programming. This curated list serves as a one-stop shop for information related to network automation.

## Core Concepts

### Infrastructure as Code

- Version-controlled network configurations
- Declarative infrastructure definitions
- Idempotent operations
- Automated testing and validation
- GitOps workflows

### Network APIs

- NETCONF - Network Configuration Protocol
- RESTCONF - REST-based network management
- gNMI - gRPC Network Management Interface
- SNMP - Simple Network Management Protocol

## Automation Tools

### Configuration Management

- **Ansible** - Agentless automation with network modules
- **SaltStack** - Event-driven automation
- **Puppet** - Declarative configuration management
- **Chef** - Infrastructure automation

### Python Libraries

- **NAPALM** - Network Automation and Programmability Abstraction Layer
- **Netmiko** - Multi-vendor SSH library
- **Nornir** - Multi-threaded automation framework
- **PyATS/Genie** - Cisco's test automation framework

### Vendor-Specific Tools

- **Juniper PyEZ** - Junos automation
- **Arista eAPI** - Arista programmability
- **Cisco NSO** - Network Services Orchestrator
- **Nokia pySROS** - Nokia SR OS automation

## Network Testing

### Validation Tools

- **Batfish** - Network configuration analysis
- **Suzieq** - Network observability platform
- **NetBox** - IP address management and network documentation
- **pytest** - Python testing framework

### Continuous Integration

- GitLab CI/CD for network configs
- Jenkins with network plugins
- GitHub Actions for network automation
- Automated compliance checking

## Data Modeling

### YANG Models

- OpenConfig - Vendor-neutral network models
- IETF standard models
- Vendor-specific extensions
- Model-driven automation

### Data Formats

- YAML for configuration
- JSON for APIs
- XML for NETCONF
- Jinja2 for templating

## Network Observability

### Monitoring

- Prometheus for metrics collection
- Grafana for visualization
- ELK stack for log analysis
- Streaming telemetry (gNMI)

### Network Mapping

- Automated topology discovery
- Diagram generation
- LLDP/CDP neighbor discovery
- BGP/OSPF relationship mapping

## Use Cases

### Common Automations

- Device provisioning (Zero Touch Provisioning)
- Configuration backups and recovery
- Compliance auditing
- Change management
- Network health checks
- Capacity planning

### Advanced Applications

- Intent-based networking
- Self-healing networks
- Predictive analytics
- Traffic engineering optimization
- Security policy automation

## SDN and Controllers

- OpenDaylight - Modular SDN platform
- ONOS - Carrier-grade SDN controller
- Ryu - Component-based SDN framework
- NSX - VMware network virtualization

## DevOps for Networking

### Best Practices

- Version control for all configs
- Peer review for changes
- Automated testing in dev/staging
- Incremental rollouts
- Rollback procedures

### Skills Required

- Python/Go programming
- REST APIs and HTTP
- YAML/JSON syntax
- Git workflow
- Linux/CLI proficiency

## Learning Resources

- Network automation courses
- Hands-on labs (EVE-NG, GNS3)
- Community forums
- Conference talks
- Open-source projects

## Pricing

Mostly free and open-source tools; some commercial options available.