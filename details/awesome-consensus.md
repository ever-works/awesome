## Overview

A curated selection of artisanal consensus algorithms and hand-crafted distributed lock services. This repository covers Paxos, Raft, and other consensus protocols used in distributed systems.

## Consensus Algorithms

### Paxos Family

- Classic Paxos - Original consensus algorithm
- Multi-Paxos - Optimized variant for multiple decisions
- Fast Paxos - Lower latency variant
- Flexible Paxos - Generalized quorum requirements
- Egalitarian Paxos (EPaxos) - Leaderless consensus

### Raft

- Understandable consensus algorithm
- Leader-based approach
- Strong consistency guarantees

### Byzantine Fault Tolerant

- PBFT - Practical Byzantine Fault Tolerance
- Tendermint - BFT consensus for blockchains
- HotStuff - Modern BFT protocol

### Other Protocols

- Zab - ZooKeeper Atomic Broadcast
- Viewstamped Replication
- Chain Replication

## Features

- Research papers and specifications
- Production implementations
- Visualization tools
- Performance comparisons
- Testing frameworks

## Production Systems Using Consensus

- Google Spanner - Uses Paxos
- Apache ZooKeeper - Uses Zab
- etcd - Uses Raft
- Consul - Uses Raft
- CockroachDB - Uses Raft

## Use Cases

- Distributed configuration management
- Leader election
- Distributed locks
- Replicated state machines
- Strongly consistent databases

## Pricing

Free and open-source algorithms and implementations.