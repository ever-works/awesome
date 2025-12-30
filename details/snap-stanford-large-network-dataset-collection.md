# SNAP Stanford Large Network Dataset Collection

**Website:** <http://snap.stanford.edu/data/>

Repository of large real-world network datasets for research on graphs, social networks, web graphs, communication patterns, and citation networks.

---

## Overview

The Stanford Large Network Dataset Collection (SNAP) provides a curated set of sizable, real-world network datasets. These datasets cover a variety of domains (social networks, trust networks, communication, online platforms, etc.) and are commonly used for research in network science, graph mining, and machine learning on graphs.

---

## Features

### General Features
- Large-scale real-world network datasets.
- Multiple network types: undirected, directed, weighted, signed, bipartite, temporal, and attributed graphs.
- Coverage of multiple domains, including:
  - Social networks
  - Trust and reputation networks
  - Online communities and forums
  - Content and interaction networks (e.g., Reddit, Wikipedia)
- Datasets often include:
  - Node and edge counts
  - Additional attributes (e.g., text, temporal information, labels)
  - Ground-truth communities for community detection benchmarking (for some collections).

### Social Network Datasets (Examples)
- **ego-Facebook**  
  - Type: Undirected  
  - Nodes: 4,039  
  - Edges: 88,234  
  - Description: Anonymized Facebook social circles.

- **ego-Gplus**  
  - Type: Directed  
  - Nodes: 107,614  
  - Edges: 13,673,453  
  - Description: Google+ social circles.

- **ego-Twitter**  
  - Type: Directed  
  - Nodes: 81,306  
  - Edges: 1,768,149  
  - Description: Twitter social circles.

- **soc-Epinions1**  
  - Type: Directed  
  - Nodes: 75,879  
  - Edges: 508,837  
  - Description: Who-trusts-whom network from Epinions.com.

- **soc-LiveJournal1**  
  - Type: Directed  
  - Nodes: 4,847,571  
  - Edges: 68,993,773  
  - Description: LiveJournal online social network.

- **soc-Pokec**  
  - Type: Directed  
  - Nodes: 1,632,803  
  - Edges: 30,622,564  
  - Description: Pokec online social network.

- **soc-Slashdot0811**  
  - Type: Directed  
  - Nodes: 77,360  
  - Edges: 905,468  
  - Description: Slashdot social network, November 2008 snapshot.

- **soc-Slashdot0922**  
  - Type: Directed  
  - Nodes: 82,168  
  - Edges: 948,464  
  - Description: Slashdot social network, February 2009 snapshot.

- **wiki-Vote**  
  - Type: Directed  
  - Nodes: 7,115  
  - Edges: 103,689  
  - Description: Wikipedia who-votes-on-whom network.

- **wiki-RfA**  
  - Type: Directed, Signed  
  - Nodes: 10,835  
  - Edges: 159,388  
  - Description: Wikipedia Requests for Adminship network with associated text.

- **gemsec-Deezer**  
  - Type: Undirected  
  - Nodes: 143,884  
  - Edges: 846,915  
  - Description: Deezer social network (Gemsec dataset).

- **gemsec-Facebook**  
  - Type: Undirected  
  - Nodes: 134,833  
  - Edges: 1,380,293  
  - Description: Facebook social network (Gemsec dataset).

- **soc-RedditHyperlinks**  
  - Type: Directed, Signed, Temporal, Attributed  
  - Nodes: 55,863  
  - Edges: 858,490  
  - Description: Hyperlinks between subreddits on Reddit.

- **soc-sign-bitcoin-otc**  
  - Type: Weighted, Signed, Directed, Temporal  
  - Nodes: 5,881  
  - Edges: 35,592  
  - Description: Bitcoin OTC web-of-trust network.

- **soc-sign-bitcoin-alpha**  
  - Type: Weighted, Signed, Directed, Temporal  
  - Nodes: 3,783  
  - Edges: 24,186  
  - Description: Bitcoin Alpha web-of-trust network.

- **comm-f2f-Resistance**  
  - Type: Weighted, Directed, Temporal  
  - Nodes: 451  
  - Edges: 3,126,993  
  - Description: Dynamic face-to-face interaction network.

- **musae-twitch**  
  - Type: Undirected  
  - Nodes: 34,118  
  - Edges: 429,113  
  - Description: Social network of Twitch users.

- **musae-facebook**  
  - Type: Undirected  
  - Nodes: 22,470  
  - Edges: 171,002  
  - Description: Facebook page–page network with page names.

- **act-mooc**  
  - Type: Bipartite, Directed, Attributed, Temporal  
  - Nodes: 7,143  
  - Edges: 411,749  
  - Description: Student actions on a MOOC platform, with student dropout binary labels.

- **musae-github**  
  - Type: Undirected  
  - Nodes: 37,700  
  - Edges: 289,003  
  - Description: Social network of GitHub developers.

- **feather-deezer-social**  
  - Type: Undirected  
  - Nodes: 28,281  
  - Edges: 92,752  
  - Description: Social network of Deezer users from Europe.

- **feather-lastfm-social**  
  - Type: Undirected  
  - Nodes: 7,624  
  - Edges: 27,806  
  - Description: Social network of Last.fm users from Asia.

- **twitch-gamers**  
  - Type: Undirected  
  - Nodes: 168,114  
  - Edges: 6,797,557  
  - Description: Social network of Twitch users.

- **congress-Twitter**  
  - Type: Directed  
  - Nodes: 475  
  - Edges: 13,289  ̵ 
  - Description: Twitter interaction network for the US Congress.

### Networks with Ground-Truth Communities (Examples)
- **com-LiveJournal**  
  - Type: Undirected, Communities  
  - Nodes: 3,997,962  
  - Edges: 34,681,189  
  - Communities: 287,512  
  - Description: LiveJournal online social network with community labels.

- **com-Friendster**  
  - Type: Undirected, Communities  
  - Nodes: 65,608,366  
  - Edges: 1,806,067,135  
  - Communities: 957,154  
  - Description: Friendster online social network with community labels.

- **com-Orkut**  
  - Type: Undirected, Communities  
  - Nodes: 3,072,441  
  - Edges: 117,185,083  
  - Communities: 6,288,363  
  - Description: Orkut online social network with community labels.

- **com-Youtube**  
  - Type: Undirected, Communities  
  - Nodes: 1,134,890  
  - Edges: 2,987,624  
  - Communities: 8,385  
  - Description: YouTube online social network with community labels.

(Additional community datasets are present on the website but truncated in the provided content.)

---

## Category
- **Directory Type:** Themed directory / dataset collection
- **Focus Areas:** Graphs, network datasets, research

---

## Brand
- **Provider:** Stanford University (SNAP – Stanford Network Analysis Project)
- **Brand Logo URL:** <https://snap.stanford.edu/snap.png>

---

## Pricing

No pricing information is provided in the given content. The collection is widely used in research; licensing or usage terms should be checked on the official website for each dataset if needed.