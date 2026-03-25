## Overview

Prometheus alerting rules that are common to every Prometheus setup. This collection provides battle-tested alert rules for various infrastructure components and applications.

## Features

### Infrastructure Alerts

#### Host and Hardware
- **Out of memory**: Host out of memory (<10% available)
- **Out of disk space**: Disk is almost full (<10% left)
- **High CPU load**: CPU load is >80%
- **Context switching**: High context switching rate
- **Swap usage**: Host swap is filling up
- **Network errors**: Network interface errors detected
- **Temperature alerts**: Hardware temperature warnings

#### Docker Containers
- **Container killed**: Container killed
- **Container absent**: Container expected but not present
- **High CPU usage**: Container CPU usage >80%
- **High memory usage**: Container memory usage >80%
- **Container down**: Container is down
- **Volume usage**: Volume usage >80%

#### Kubernetes
- **Node not ready**: Kubernetes node not ready
- **Memory pressure**: Node under memory pressure
- **Disk pressure**: Node under disk pressure
- **Out of capacity**: Node out of capacity
- **Pod crash looping**: Pod is crash looping
- **Pod not healthy**: Pod not healthy
- **Deployment replicas mismatch**: Deployment replicas don't match desired
- **StatefulSet replicas mismatch**: StatefulSet issues
- **PersistentVolume errors**: PV claim issues
- **Job failures**: Job has failed

### Database Alerts

#### PostgreSQL
- **Down**: PostgreSQL down
- **Replication lag**: Replication lag is too high
- **Too many connections**: Too many connections (>80%)
- **Dead locks**: Deadlock detected
- **Slow queries**: Slow query detected
- **High rollback rate**: Unusual rollback rate
- **Table not vacuumed**: Table not vacuumed

#### MySQL
- **Down**: MySQL down
- **Too many connections**: Connection limit reached
- **High thread running**: Too many threads running
- **Slave replication lag**: Replication lag
- **Slow queries**: Slow query log growing
- **InnoDB log waits**: InnoDB log wait detected

#### MongoDB
- **Down**: MongoDB down
- **Replication lag**: Replication lag
- **Replication headroom**: Low oplog window
- **Number of cursors open**: Too many cursors
- **Cursors timeout**: Cursors timing out
- **Too many connections**: Connection limit

#### Redis
- **Down**: Redis down
- **Out of memory**: Redis out of memory
- **Too many connections**: Connection limit
- **Rejected connections**: Connections rejected
- **Replication broken**: Replication link down

### Web Server Alerts

#### Nginx
- **High HTTP error rate**: 4xx/5xx errors >5%
- **High request rate**: Unusual request rate
- **Latency high**: Request latency high

#### Apache
- **Down**: Apache down
- **Workers load**: All workers busy
- **Restart**: Apache restarted

### Message Queue Alerts

#### RabbitMQ
- **Down**: RabbitMQ down
- **Cluster down**: Node down
- **Cluster partition**: Network partition detected
- **Out of memory**: Node out of memory
- **Too many connections**: Connection limit
- **Unroutable messages**: Messages not routed
- **Queue size**: Queue growing

#### Kafka
- **Broker down**: Kafka broker down
- **Under replicated partitions**: Partitions under replicated
- **Offline partitions**: Partitions offline
- **Consumer lag**: Consumer lag growing
- **ISR shrink rate**: In-sync replicas shrinking

### Application Alerts

#### SSL/TLS
- **Certificate expiry**: Certificate expiring soon
- **Certificate errors**: Certificate validation errors

#### Blackbox Exporter
- **Probe failed**: Probe failed
- **Slow probe**: Probe taking too long
- **HTTP status code**: Unexpected HTTP status
- **SSL certificate**: SSL certificate expiring

#### Java/JVM
- **High memory**: JVM memory usage high
- **High GC time**: Garbage collection time high
- **Thread deadlock**: Thread deadlock detected

### Cloud Platform Alerts

#### AWS
- **EC2 instance down**: Instance terminated
- **RDS issues**: Database issues
- **ELB unhealthy targets**: Unhealthy targets

#### GCP
- **Instance down**: Compute instance down
- **Load balancer issues**: Backend issues

### Best Practices

#### Alert Severity Levels
- **Critical**: Immediate action required
- **Warning**: Investigation needed
- **Info**: Informational only

#### Alert Annotations
- Clear description
- Runbook links
- Dashboard links
- Affected service

#### Alert Configuration
- Appropriate thresholds
- Sufficient evaluation period
- Avoid alert fatigue
- Group related alerts
- Use inhibition rules

### Integration

#### Alertmanager
- Route to different receivers
- Group by severity/service
- Silence and inhibit rules
- Template customization

#### Notification Channels
- Slack, PagerDuty, OpsGenie
- Email, SMS
- Webhooks for custom integrations
- ChatOps platforms

### Alert Rule Structure

```yaml
groups:
  - name: example
    rules:
    - alert: HighMemoryUsage
      expr: node_memory_Active_bytes / node_memory_MemTotal_bytes > 0.9
      for: 5m
      labels:
        severity: warning
      annotations:
        summary: High memory usage detected
        description: Memory usage is above 90%
```

## Use Cases

- Infrastructure monitoring and alerting
- Application performance monitoring
- Database health monitoring
- Kubernetes cluster monitoring
- Service availability tracking
- SLO/SLA compliance monitoring
- Capacity planning alerts
- Security incident detection

## Pricing

Free and open-source. The alert rules are provided as-is and can be customized for your environment. Prometheus and Alertmanager are also free and open-source projects.