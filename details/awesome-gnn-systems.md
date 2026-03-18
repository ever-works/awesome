## Overview

Awesome GNN Systems focuses on the systems and infrastructure aspects of graph neural networks, covering frameworks, distributed training, and production deployment of GNN models at scale.

## GNN Frameworks

### PyTorch Geometric (PyG)
- Most popular GNN library
- Built on PyTorch
- Rich model zoo
- Efficient mini-batching

### DGL (Deep Graph Library)
- Developed by AWS
- Framework-agnostic design
- Distributed training support
- Production-ready features

### TensorFlow GNN
- Google's GNN framework
- TensorFlow integration
- Scalable training

## Distributed Training Systems

### DistDGL
Distributed extension of DGL for training massive graphs across multiple machines.

### PyG Distributed
Scales PyTorch Geometric to billion-node graphs with distributed training.

### GraphLearn
Alibaba's system for large-scale graph learning with sampling and training.

## Graph Sampling

Efficient sampling strategies:
- Neighbor sampling
- Layer-wise sampling
- Random walk sampling
- Importance sampling

## Production Deployment

### Serving Systems
- TorchServe for GNN models
- TensorFlow Serving
- Custom serving infrastructure

### Optimization
- Model quantization
- Pruning techniques
- Knowledge distillation
- Hardware acceleration (GPU, TPU)

## Applications

- Social network analysis
- Recommendation systems
- Drug discovery
- Traffic prediction
- Fraud detection
- Knowledge graphs