## Overview

A comprehensive curated list of resources about gameplay network programming. Game networking is a specialized subset of computer networking that focuses on data replication, state synchronization, and RPCs for multiplayer online games.

## Core Concepts

### Network Architectures

- **Client-Server** - Traditional centralized architecture
- **Peer-to-Peer** - Decentralized player connections
- **Listen Server** - One client acts as server
- **Dedicated Server** - Separate server instance
- **Hybrid Approaches** - Combining multiple architectures

### State Synchronization

- Snapshot interpolation
- Client-side prediction
- Server reconciliation
- Lag compensation techniques
- Delta compression

### Network Optimization

- **Bandwidth Optimization**
  - Entity relevance filtering
  - Area of interest management
  - Prioritized replication
  - Quantization and compression

- **Latency Mitigation**
  - Client prediction
  - Server-side rewinding
  - Input buffering
  - Lag compensation

## Technologies and Protocols

### Transport Protocols

- UDP - for real-time gameplay
- TCP - for reliable data
- WebRTC - for browser-based games
- QUIC - modern low-latency protocol

### Networking Libraries

- **Photon** - Cross-platform multiplayer networking
- **Mirror** - Unity networking solution
- **Netcode for GameObjects** - Unity's official netcode
- **ENet** - Reliable UDP library
- **SteamWorks** - Steam networking API
- **PlayFab** - Backend services for games

## Game Genres and Approaches

### Fast-Paced Games (FPS, Racing)

- Heavy client prediction
- Frequent state updates
- Aggressive lag compensation
- Low tick rates with interpolation

### Strategy Games (RTS, MOBA)

- Deterministic lockstep
- Command-based networking
- Rollback on desync
- Synchronized random number generation

### MMORPGs

- Interest management
- Sharded architecture
- Database-backed persistence
- Instance servers

## Security Considerations

- Anti-cheat systems
- Server authority
- Input validation
- Rate limiting
- Encryption for sensitive data

## Testing and Debugging

- Network simulators (latency, packet loss)
- Replay systems
- Network profiling tools
- Stress testing frameworks

## Learning Resources

- GDC talks on network programming
- Gaffer on Games articles
- Game engine documentation
- Open-source game implementations

## Pricing

Mostly free and open-source libraries and resources.