## Overview

A comprehensive reading list of research papers about distributed consensus, organized into theory papers and implementation papers. Essential resource for understanding consensus algorithms that power distributed systems.

## Theory Papers

### Classic Consensus

- Paxos - Leslie Lamport's foundational algorithm
- Viewstamped Replication - Barbara Liskov's approach
- Virtual Synchrony - Group communication model
- Byzantine Generals Problem - Fault tolerance foundations

### Modern Variants

- Multi-Paxos - Optimized for multiple decisions
- Fast Paxos - Lower latency variant
- Egalitarian Paxos (EPaxos) - Leaderless consensus
- Flexible Paxos - Generalized quorums

### Byzantine Fault Tolerance

- PBFT - Practical Byzantine Fault Tolerance
- HotStuff - Modern BFT for blockchain
- Tendermint - BFT consensus for Cosmos
- SBFT - Scalable Byzantine Fault Tolerance

## Implementation Papers

### Production Systems

- Chubby - Google's lock service
- ZooKeeper - Apache distributed coordination
- etcd - CoreOS distributed key-value store
- Consul - HashiCorp service mesh

### Database Systems

- Spanner - Google's globally distributed database
- CockroachDB - Distributed SQL database
- TiDB - MySQL-compatible distributed database
- YugabyteDB - PostgreSQL-compatible DB

### Blockchain Systems

- Bitcoin - Proof of Work consensus
- Ethereum - Proof of Stake (Casper)
- Algorand - Pure Proof of Stake
- Avalanche - Snow family protocols

## Key Concepts

### Consensus Properties

- **Agreement** - All correct processes agree on same value
- **Validity** - Agreed value was proposed by some process
- **Termination** - All correct processes eventually decide
- **Integrity** - Each process decides at most once

### Failure Models

- Crash failures - Processes stop executing
- Omission failures - Messages lost
- Timing failures - Delays exceed bounds
- Byzantine failures - Arbitrary behavior

## Algorithm Families

### Leader-Based

- Single leader coordinates decisions
- Examples: Paxos, Raft, Viewstamped Replication
- Pros: Simple, efficient in common case
- Cons: Leader election overhead, single point of contention

### Leaderless

- No distinguished coordinator
- Examples: EPaxos, HotStuff variants
- Pros: No leader election, better load distribution
- Cons: Complex protocol, higher message complexity

### Quorum-Based

- Decisions require majority agreement
- Flexible quorum configurations
- Read and write quorums
- Intersection property

## Performance Considerations

### Latency

- Message round trips
- Wide-area network effects
- Failure detection time
- Recovery overhead

### Throughput

- Batching strategies
- Pipeline parallelism
- Concurrent consensus instances
- Hardware acceleration

### Scalability

- Number of nodes
- Geographic distribution
- Read vs write scaling
- State machine replication

## Verification and Testing

- TLA+ specifications
- Model checking
- Formal proofs
- Randomized testing
- Jepsen testing framework

## Research Venues

- PODC - Principles of Distributed Computing
- DISC - International Symposium on Distributed Computing
- OSDI - Operating Systems Design and Implementation
- SOSP - Symposium on Operating Systems Principles

## Pricing

Free and open-source research papers and specifications.