## Overview

Graphiti is a framework for building and querying temporal context graphs for AI agents. Unlike traditional knowledge graphs, it tracks how facts change over time and maintains provenance to source data.

## Key Features

### Temporal Tracking

- Facts have timestamps and validity periods
- Track changes in relationships over time
- Example: "Kendra loves Adidas shoes (as of March 2026)"
- Historical context preservation

### Provenance Management

- Link facts to source data
- Track information lineage
- Verify fact origins
- Audit trails for AI decisions

### AI Agent Integration

- Real-time knowledge graph updates
- Context-aware query interfaces
- Integration with LLMs
- Reasoning over temporal data

## Use Cases

### Conversational AI

- Track user preferences over time
- Maintain conversation history
- Understand changing context
- Personalized responses

### Recommendation Systems

- Evolving user interests
- Trending patterns
- Temporal collaborative filtering
- Time-aware recommendations

### Enterprise Knowledge Management

- Organizational changes tracking
- Employee relationship evolution
- Project timeline management
- Historical decision context

## Architecture

### Graph Model

- Nodes: Entities with temporal attributes
- Edges: Relationships with validity periods
- Properties: Time-stamped attributes
- Metadata: Provenance information

### Query Capabilities

- Point-in-time queries ("What was true then?")
- Change tracking ("What changed?")
- Temporal aggregations
- Trend analysis

## Benefits

- Enhanced AI agent reasoning
- Better context understanding
- Explainable AI decisions
- Audit and compliance support
- Historical analysis capabilities

## Integration

- LLM frameworks (LangChain, etc.)
- Vector databases
- Graph databases (Neo4j, etc.)
- RAG pipelines

## Pricing

Free and open-source framework.