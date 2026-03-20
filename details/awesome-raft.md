## Overview

Raft is a consensus algorithm designed to be easy to understand while remaining equivalent to Paxos in fault-tolerance and performance. This repository collects Raft implementations, papers, and resources.

## What is Raft?

Raft is a distributed consensus algorithm that allows a collection of machines to work as a coherent group that can survive the failures of some of its members. It's designed to be more understandable than Paxos.

## Popular Implementations

- **etcd/raft** - Go implementation used inside etcd, powering Kubernetes and thousands of production clusters
- **hashicorp/raft** - Go implementation used in HashiCorp applications
- **tikv/raft-rs** - Rust implementation by TiKV
- **brpc/braft** - C++ implementation by Baidu Inc.
- **sofa-jraft** - Java implementation by Alipay Inc.

## Production Usage

Raft powers major distributed systems including:

- etcd - Distributed key-value store
- Kubernetes - Container orchestration
- CockroachDB - Distributed SQL database
- TiDB - Distributed database
- Docker Swarm - Container orchestration
- Cloud Foundry Diego
- Project Calico
- Hyperledger

## Features

- Leader election
- Log replication
- Safety guarantees
- Membership changes
- Log compaction

## Learning Resources

- Original Raft paper
- Interactive visualizations
- Implementation guides
- Production case studies

## Pricing

Free and open-source implementations.