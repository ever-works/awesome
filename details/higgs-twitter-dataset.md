# Higgs Twitter Dataset

**Source:** SNAP (Stanford Network Analysis Project)  
**URL:** http://snap.stanford.edu/data/higgs-twitter.html  
**Category:** Themed Directories / Social Network Datasets  
**Brand:** snap-stanford

## Overview
The Higgs Twitter Dataset captures Twitter activity related to the announcement of the discovery of a particle with the features of the Higgs boson on 4 July 2012. It includes tweets from 1–7 July 2012 and provides multiple directed networks derived from user interactions during this period.

All user IDs are anonymized and consistently mapped across all networks, enabling multiplex/multilayer network analysis that combines social structure and different interaction dynamics.

**Last update:** 31 March 2015 (earlier downloaded versions may yield different results).

## Features

### Temporal Coverage
- Time window: 1–7 July 2012
- Focus: Twitter activity before, during, and after the Higgs boson discovery announcement on 4 July 2012

### Network Layers Provided
1. **Retweet Network**
   - Derived from retweeting activity
   - Directed edges represent retweet actions between users

2. **Reply Network**
   - Derived from replies to existing tweets
   - Directed edges represent reply actions

3. **Mention Network**
   - Derived from mentions of other users within tweets
   - Directed edges represent mention actions
   - Users mentioned in retweeted tweets are also counted as mentions (e.g., if @A retweets a tweet by @B saying "hello @C @D", links created: `@A @B timeX RT`, `@A @C timeX MT`, `@A @D timeX MT`)

4. **Social (Friends/Followers) Network**
   - Encodes follower/followee relationships among users involved in the above activities

5. **Activity / Interaction Data**
   - Information about user-level activity on Twitter during the discovery event

### Anonymization & Multiplex Structure
- User IDs are anonymized
- The same anonymized user IDs are used consistently across all networks
- Supports analysis of large-scale interdependent / interconnected multiplex or multilayer networks:
  - One layer for social structure (friends/followers)
  - Three layers for user dynamics (retweet, reply, mention)

### Data Format
**File:** `higgs-activity_time.txt`

Each line:
```text
userA userB timestamp interaction
```
- `userA`: initiating user
- `userB`: target user
- `timestamp`: time of the interaction
- `interaction` (directed link type):
  - `RT` – retweet
  - `MT` – mention
  - `RE` – reply

Notes on directionality:
- Links are provided as observed actions: who retweets/mentions/replies/follows whom.
- For information-flow analysis, researchers may choose to reverse some directions (e.g., retweets), depending on the application.

### Social Network (Friends/Followers) Statistics
- Nodes: **456,626**
- Edges: **14,855,842**
- Nodes in largest WCC: **456,290** (0.999)
- Edges in largest WCC: **14,855,466** (1.000)
- Nodes in largest SCC: **360,210** (0.789)
- Edges in largest SCC: **14,102,605** (0.949)
- Average clustering coefficient: **0.1887**
- Number of triangles: **83,023,401**
- Fraction of closed triangles: **0.002901**
- Diameter (longest shortest path): **9**
- 90-percentile effective diameter: **3.7**

### Retweet Network Statistics
- Nodes: **256,491**
- Edges: **328,132**
- Nodes in largest WCC: **223,833** (0.873)
- Edges in largest WCC: **308,596** (0.940)
- Nodes in largest SCC: **984** (0.004)
- Edges in largest SCC: **3,850** (0.012)
- Average clustering coefficient: **0.0156**
- Number of triangles: **21,172**
- Fraction of closed triangles: **0.0001085**
- Diameter (longest shortest path): **19**
- 90-percentile effective diameter: **6.8**

### Reply Network Statistics
- Nodes: **38,918**
- Edges: **32,523**
- Nodes in largest WCC: **12,839** (0.330)
- Edges in largest WCC: **14,944** (0.459)
- Nodes in largest SCC: **322** (0.008)
- Edges in largest SCC: **708** (0.022)
- Average clustering coefficient: **0.0058**
- Number of triangles: **244**
- Fraction of closed triangles: **0.0001561**
- Diameter (longest shortest path): **29**
- 90-percentile effective diameter: **10**

### Mention Network Statistics
- Nodes: **116,408**
- Edges: **150,818**
- Nodes in largest WCC: **91,606** (0.787)
- Edges in largest WCC: **132,068** (0.876)
- Nodes in largest SCC: **1,801** (0.015)
- Edges in largest SCC: **7,069** (0.047)
- Average clustering coefficient: **0.0825**
- Number of triangles: **23,068**
- Fraction of closed triangles: **0.0002417**
- Diameter (longest shortest path): **18**
- 90-percentile effective diameter: **6.5**

## Use Cases
- Analysis of information diffusion around major scientific events
- Study of multiplex / multilayer social networks
- Research on social structure vs. interaction dynamics (retweets, replies, mentions)
- Benchmarking graph algorithms on large real-world directed networks

## Pricing
- Not specified in the provided content (dataset is part of the SNAP collection; check source page for any licensing or usage terms).