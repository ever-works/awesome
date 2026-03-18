## Overview

Awesome Deep GNN collects research on building deeper graph neural networks. Deep GNNs face unique challenges compared to traditional deep learning, particularly the oversmoothing problem where node features become indistinguishable with many layers.

## The Oversmoothing Problem

As GNNs get deeper, node representations converge to similar values, losing discriminative power. This limits most GNNs to 2-3 layers.

## Solutions & Techniques

### Residual Connections
Skip connections similar to ResNet enable gradient flow through deep networks.

### Normalization Techniques
- Batch normalization
- Layer normalization
- Pair normalization
- Graph normalization

### Sampling Strategies
Neighborhood sampling prevents exponential growth of receptive fields.

### Jumping Knowledge Networks
Adaptively aggregate information from different layers.

### Graph Rewiring
Modify graph structure to improve information flow.

## Deep GNN Architectures

### GCNII
Simple and Deep Graph Convolutional Networks with initial residual connections.

### DeeperGCN
Applies techniques from CNNs (pre-activation, res+) to GNNs.

### GPNN
Graph Polynomial Neural Networks for very deep architectures.

## Research Areas

- Theoretical analysis of depth in GNNs
- Novel architectures for deep propagation
- Training techniques and optimization
- Benchmarking and evaluation

## Applications

Deep GNNs show improvements in:
- Long-range dependency modeling
- Heterophilic graphs
- Large-scale graph learning
- Graph generation