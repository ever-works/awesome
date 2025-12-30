# Twitter Ego Datasets

**Category:** Themed Directories  
**Tags:** datasets, social, graph  
**Source:** [SNAP (Stanford Network Analysis Project)](http://snap.stanford.edu/data/egonets-Twitter.html)

## Description
The Twitter Ego Datasets are social network graph datasets capturing Twitter ego-networks and circles (lists) collected from public data. Each dataset focuses on user-centric neighborhoods and includes node features (user profiles), circle memberships, and ego-network structures. These datasets are part of the SNAP social circles collection, alongside comparable datasets for Facebook and Google+.

## Features
- **Data type:** Social network graph data from Twitter
- **Structure:**
  - Ego-networks (user-centric neighborhood graphs)
  - Circles / lists (groupings of neighbors)
  - Node features representing user profiles
- **Scale and statistics:**
  - Nodes: 81,306
  - Edges: 1,768,149
  - Nodes in largest weakly connected component (WCC): 81,306 (1.000)
  - Edges in largest WCC: 1,768,149 (1.000)
  - Nodes in largest strongly connected component (SCC): 68,413 (0.841)
  - Edges in largest SCC: 1,685,163 (0.953)
  - Average clustering coefficient: 0.5653
  - Number of triangles: 13,082,506
  - Fraction of closed triangles: 0.06415
  - Diameter (longest shortest path): 7
  - 90th-percentile effective diameter: 4.5
- **Comparative datasets available:** Matching ego-network datasets also available for Facebook and Google+ (separate resources).

## Files
- **`twitter.tar.gz`**
  - Twitter ego-network collection
  - Contains 973 individual networks
- **`twitter_combined.txt.gz`**
  - All egonet edges combined into a single edge list file
- **`readme-Ego.txt`**
  - Documentation describing file formats and dataset organization

## Usage
Suitable for research and analysis in:
- Ego-network structure and social circle detection
- Community detection and clustering in social graphs
- Link prediction and network evolution modeling
- Node classification and profiling based on user features

## Pricing
- Not specified; distributed as an academic dataset via SNAP (typically freely available for research and educational use, subject to SNAP’s terms).