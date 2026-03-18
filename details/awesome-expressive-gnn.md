## Overview

Awesome Expressive GNN focuses on the theoretical expressiveness of graph neural networks - their ability to distinguish between different graph structures and learn complex functions on graphs.

## Weisfeiler-Leman Test

The WL test is a graph isomorphism test that provides the theoretical basis for understanding GNN expressiveness. Standard message-passing GNNs are at most as powerful as 1-WL.

## Expressiveness Hierarchy

### Standard MPNNs
Message Passing Neural Networks (MPNNs) have limited expressiveness, equivalent to 1-WL test.

### Higher-Order Methods
- k-WL GNNs: More powerful but computationally expensive
- Subgraph GNNs: Operate on subgraph patterns
- Graph Transformer: Attention-based architectures

## Key Papers

**How Powerful are Graph Neural Networks?**
Introduced GIN (Graph Isomorphism Network), maximally expressive within MPNN framework.

**Weisfeiler and Leman Go Neural**
Theoretical foundations connecting WL test to GNN expressiveness.

## Beyond 1-WL Expressiveness

### Subgraph Methods
- Extract and process subgraphs
- Higher computational cost
- Provably more expressive

### High-Dimensional Features
- Random features
- Structural encodings
- Positional encodings

### Graph Transformers
- Global attention mechanisms
- Theoretically complete expressiveness
- Computational challenges

## Practical Implications

- Understanding when standard GNNs suffice
- Choosing appropriate architectures
- Balancing expressiveness vs. efficiency
- Task-specific considerations

## Benchmarks

Standard benchmarks for testing expressiveness:
- ZINC molecular graphs
- PATTERN/CLUSTER synthetic tasks
- Graph property prediction tasks