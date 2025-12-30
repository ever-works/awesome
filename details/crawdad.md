# CRAWDAD – Wireless Network Data Archive

**Category:** Themed Directories  
**Slug:** `crawdad`  
**Brand:** Dartmouth College  
**Source:** https://ieee-dataport.org/open-access/crawdad-duepacket-delivery

CRAWDAD is a community-maintained archive and directory of real‑world wireless network data, traces, and related datasets (such as pcap files). It catalogs datasets from multiple contributors to support reproducible research in wireless and mobile networking.

---

## Overview of This Dataset: `due/packet-delivery`

Wireless sensor network (WSN) link performance dataset collected indoors over 6 months, covering:
- ~50,000 parameter configurations for 7 key protocol stack parameters
- Meta‑data for nearly 200 million transmitted packets
- 4 major performance metrics: **energy, throughput, delay, loss**

**Key metadata**:
- **Nickname:** `packet-delivery`
- **Institution:** University of Duisburg-Essen and Norwegian University of Science and Technology
- **Measurement period:** 2012‑11‑01 to 2013‑11‑30
- **Release date:** 2015‑03‑30
- **Last modified:** 2015‑03‑30
- **DOI:** https://dx.doi.org/10.15783/C7NP4Z

---

## Environment & Methodology

### Collection Environment
- Location: Long hallway in a university building
- Dimensions: 2 m × 40 m
- Node mounting height: 0.7 m (wooden stands)
- Line-of-sight maintained between two motes
- Sender–receiver distances: **10, 15, 20, 25, 30, 35 m**
- Human presence: Students and employees may walk in the hallway during experiments

### Network Configuration Parameters
For each experiment, the following parameters are varied:
- **Packet inter‑arrival time (ms):** 10, 15, 20, 25, 30, 35, 40, 50
- **Packet payload size (bytes):** 20, 35, 50, 65, 80, 95, 110
- **Maximum queue size (packets):** 1, 30, 60
- **Max_tries (max transmissions):** 1, 3, 5
- **Retry delay (ms):** 30, 60
- **Transmission power level:** 3, 7, 11, 15, 19, 23, 27, 31
- **Distance (m):** 10, 15, 20, 25, 30, 35

### Data Collection Methodology
- Metadata of each packet recorded at **sender** and **receiver** nodes
- Data forwarded via USB cables to a laptop
- Contains no sensitive or personal information → **no sanitization performed**

---

## Traceset: `due/packet-delivery/delay`

Per‑packet delay measurements under various stack parameter configurations.

**General info:**
- **Files:**
  - `delay_10m_12runs.rar`
  - `delay_15m_11runs.rar`
  - `delay_20m_10runs.rar`
  - `delay_25m_9runs.rar`
  - `delay_30m_11runs.rar`
  - `delay_35m_9runs.rar`
- **Content:** 6 traces (one per distance), each with delay measurements for ~a dozen runs
- **Delay definition:** Time between packet generation at sender and packet reception at receiver
- **Measurement purpose:** Network performance analysis
- **Dataname:** `due/packet-delivery/delay`
- **Version:** `20150401` (initial version)
- **Last modified / Release date:** 2015‑03‑30
- **Nickname:** `delay`

### Example Trace: `10meter`
- Content: Delay measurements of all packets transmitted at 10 m
- **Format:**
  - Each file has **8064 lines**
  - Each line corresponds to one stack parameter configuration
  - Line structure:
    - `period | packet length | queue_size | max_retries | retry_delay | TxP_level | distance | average_SNR | delay_run1_pkt1 | ... | delay_run1_pkt300 | delay_run2_pkt1 | ... | delay_run2_pkt300 | ... | delay_runN_pkt1 | ... | delay_runN_pkt300`
  - Special values:
    - `9999` or `1111` indicate packets not received or delay measurement errors

---

## Features

- Community‑maintained directory for wireless and mobile networking datasets
- Provides real‑world wireless network traces and related data (including per‑packet metadata)
- Supports reproducible research via well‑documented experimental setups and parameter sweeps
- Includes large‑scale WSN link measurements:
  - Multi‑month measurement campaigns
  - Tens of thousands of parameter configurations
  - Hundreds of millions of packets
- Captures key performance metrics for wireless links:
  - Energy, throughput, delay, packet loss
- Offers structured trace files with detailed parameter fields for each configuration
- Includes explicit experiment context: topology, environment, distances, human presence
- Uses open research data practices (DOI, versioning, descriptive metadata)

---

## Pricing

Not specified. The referenced dataset is listed as **open access** on IEEE Dataport.