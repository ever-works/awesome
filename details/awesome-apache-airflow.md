## Overview

Apache Airflow is a platform to programmatically author, schedule, and monitor workflows. This list collects resources for learning and mastering Airflow.

## Features

### Core Capabilities
- Dynamic pipeline generation with Python code
- Extensible through custom operators and hooks
- Rich scheduling and execution semantics
- Web UI for pipeline monitoring and management
- Integration with major cloud platforms and databases
- Scalable distributed execution

### Official Providers and Integrations

#### Cloud Platforms
- AWS (S3, EMR, Redshift, SageMaker, Athena)
- Google Cloud (BigQuery, GCS, Dataproc, Composer)
- Azure (Blob Storage, Data Factory, Databricks)

#### Databases
- PostgreSQL, MySQL, SQL Server
- MongoDB, Cassandra, Redis
- Snowflake, BigQuery, Redshift

#### Data Processing
- Apache Spark (via EMR, Dataproc, or standalone)
- Apache Kafka and Kafka Connect
- dbt (data build tool)
- Great Expectations (data quality)

#### Container Orchestration
- Kubernetes (KubernetesPodOperator)
- Docker (DockerOperator)
- ECS and Fargate

### Popular Plugins and Extensions
- **astronomer-cosmos**: Run dbt projects as Airflow DAGs
- **airflow-dbt**: Integration with dbt
- **airflow-exporter**: Prometheus metrics exporter
- **airflow-diagrams**: Generate visual diagrams of DAGs

### Managed Services
- **Astronomer**: Enterprise Airflow platform
- **Google Cloud Composer**: Fully managed Airflow
- **AWS MWAA**: Managed Workflows for Apache Airflow
- **Qubole**: Data lake platform with Airflow

### Development Tools
- **airflow-testing**: Testing frameworks for DAGs
- **airflow-maintenance-dags**: Utility DAGs for cleanup
- **airflow-code-editor**: Edit DAGs in web UI
- **astronomer-airflow-cli**: CLI for local development

### Best Practices
- DAG design patterns and anti-patterns
- Testing strategies for workflows
- Performance optimization techniques
- Deployment and CI/CD workflows
- Monitoring and alerting setup
- Security and access control

### Learning Resources
- Official Apache Airflow documentation
- Airflow Summit talks and presentations
- Blog posts and tutorials
- Books: "Data Pipelines with Apache Airflow"
- Astronomer documentation and guides

## Use Cases

- Batch ETL/ELT pipelines
- ML model training and deployment workflows
- Data warehouse maintenance and analytics
- Report generation and distribution
- API data ingestion
- Cross-system data synchronization
- Monitoring and alerting workflows

## Pricing

Apache Airflow is free and open-source under the Apache 2.0 license. Managed services have subscription or usage-based pricing.