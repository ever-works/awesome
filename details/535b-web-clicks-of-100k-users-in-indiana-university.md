# 53.5B Web Clicks of 100K Users in Indiana University

## Overview
A large-scale clickstream dataset of approximately **53.5 billion HTTP requests** collected at Indiana University (IU), capturing web browsing activity of about **100,000 anonymized users**. The data supports research on web traffic networks, user browsing behavior, recommendation systems, and network traffic patterns.

Data was captured at IU’s border router using packet-level collection, enabling analysis of real user navigation paths (via referrer information) while minimizing biases typical of server logs or browser-based data.

## Features

### Scope and Scale
- ~53.5 billion HTTP GET requests
- ~60 million requests per day
- ~30 GB/day of raw traffic during collection
- Collection period: **September 2006 – May 2010**
- Data missing for about **275 days** total
- Approximately **0.85 TB** (raw) + **1.5 TB** (raw-url) compressed

### Collections
1. **`raw` collection**
   - ~25 billion requests
   - Referrer: only **host name** of the referrer retained
   - Time span: **26 Sep 2006 – 3 Mar 2008**
   - Missing 98 days of data (including entire **June 2007**)
   - Size: ~**0.85 TB**, compressed

2. **`raw-url` collection**
   - ~28.6 billion requests
   - Referrer: **full referrer URL** retained
   - Time span: **3 Mar 2008 – 31 May 2010**
   - Missing 179 days of data, including full months of **Dec 2008, Jan 2009, Feb 2009**
   - Size: ~**1.5 TB**, compressed

### Data Collection Methodology
- Source: Mirror of traffic passing through **Indiana University’s border router**
- Filter: **Berkeley Packet Filter** matching all traffic to **TCP port 80**
- Tooling: Long-running collection process using the **pcap** library
- Extraction: Regular expressions applied to packet payloads to identify **HTTP GET** requests
- Only requests are logged; server responses are not analyzed
- No TCP stream reassembly performed

### Recorded Fields per Request
Each logged record includes:
- **Timestamp** (32-bit Unix epoch in seconds, little-endian)
- **Requested URL** (split into `host` and `path` fields)
- **Referring URL / host** (depending on collection: hostname only or full URL)
- **User agent classification**:
  - Browser (`"B"`) vs. other/unknown/bot (`"?"`)
- **Direction flag** (traffic origin/destination relative to IU):
  - `"I"` – External traffic to IU (outside → IU)
  - `"O"` – Internal traffic from IU to the outside (IU → outside)

### Traffic Coverage and Sampling Notes
1. **Inside vs. outside IU traffic**
   - "Outside IU" traffic: requests from **outside IU** for **pages inside IU**
   - "Inside IU" traffic: requests from **people at IU (~100,000 users)** for **resources outside IU**
   - These two sets have different and important sampling biases

2. **Anonymization and privacy**
   - No client-identifying data retained:
     - No MAC addresses
     - No IP addresses
     - No unique client indices

3. **Limitations**
   - No stream reassembly; only individual packets with GET requests
   - Server responses not logged
   - Only HTTP (port 80) traffic captured

### File Organization and Format
- Dataset is **broken into hourly files**
- First line of each file: a set of flags (can be ignored by most users)
- Each record has the structure:

  ```
  XXXXADreferrer
  host
  path
  ```

  Where:
  - `XXXX` – 32-bit Unix epoch timestamp (seconds, little-endian)
  - `A` – User-agent flag:
    - `"B"` = browser
    - `"?"` = other (including bots)
  - `D` – Direction flag:
    - `"I"` = external traffic to IU
    - `"O"` = internal traffic from IU to outside
  - `referrer` – Referrer hostname or full URL (newline-terminated)
  - `host` – Target hostname (newline-terminated)
  - `path` – Target path (newline-terminated)

## Potential Applications
- Modeling the **structure and dynamics of web traffic networks**
- Studying **user browsing behavior** and navigation paths
- Developing and evaluating **recommendation systems**
- Analyzing **network traffic patterns** and workload characteristics
- Designing and optimizing **network infrastructure**, **websites**, and **server software**
- **Forecasting traffic trends**
- **Classifying websites** by activity patterns
- Improving **ranking algorithms** for search results

## Source
- More information and access: [http://cnets.indiana.edu/groups/nan/webtraffic/click-dataset/](http://cnets.indiana.edu/groups/nan/webtraffic/click-dataset/)