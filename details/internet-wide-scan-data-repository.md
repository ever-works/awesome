## Internet-Wide Scan Data Repository

Public archive of large-scale Internet-wide scan and security research datasets, hosted by the Stanford Empirical Security Research Group (ESRG) and open to other researchers.

- **Website:** https://scans.io/
- **Category:** Themed directories
- **Tags:** datasets, security, networking
- **Usage restriction:** Non-commercial use only
- **API/Interface:** JSON interface available at `/json`

---

### Features

#### General Repository Features
- Public archive of research datasets describing Internet hosts, services, and websites.
- Hosted by Stanford Empirical Security Research Group (ESRG).
- Supports hosting datasets from external researchers, not just Stanford.
- Focus on Internet-wide measurements and security-relevant data.
- Non-commercial use restriction for all hosted data.
- JSON interface for programmatic access to repository contents.

#### Included / Linked Datasets

**1. Censys Universal Internet Dataset**  
_External dataset from Censys, Inc._
- Daily snapshots of public IPv4 and IPv6 hosts.
- Continuous scanning of ~1,000 ports, with prediction of services on all 65,535 ports.
- Performs protocol detection and full protocol handshakes.
- Labels known software and devices.
- Approx. 3.3 billion services represented.
- Daily snapshot size: ~2 TB.

**2. Censys Universal Certificate Dataset**  
_External dataset from Censys, Inc._
- Append-only store of X.509 certificates.
- Sources: public Certificate Transparency (CT) logs and Internet scans.
- Includes:
  - Raw PEM-encoded certificates.
  - Parsed X.509 structured data.
  - Browser validation and revocation information.
  - CT log entries.
  - ZLint validation results.
- Scale: ~8 billion certificates.
- Total size: ~15–20 TB.

**3. Project Sonar Open Data Repository**  
_External dataset from Rapid7, Inc._
- Internet-wide surveys focused on exposure to common vulnerabilities.
- Regular Internet-wide scanning data.
- Multiple DNS datasets, including:
  - Reverse PTR lookups of all IPv4 addresses.
- Intended for security and Internet measurement research.

#### Paper Artifacts / Study Datasets

**4. Cloud Watching: Understanding Attacks Against Cloud-Hosted Services**  
_Stanford University paper artifacts_
- Study of how attackers identify and target cloud services vs.
  - Traditional enterprise networks.
  - Network telescopes.
- Uses a diverse set of honeypots:
  - Deployed across 5 cloud providers.
  - Located in 23 countries.
  - Plus 2 educational networks and 1 network telescope.
- Analyzes influence of:
  - IP address assignment.
  - Geography.
  - Network characteristics.
  - Service/port selection.
- Key findings include:
  - Scanners targeting cloud compute are selective.
  - They avoid scanning networks without legitimate services.
  - They discriminate between geographic regions.
  - Attackers mine Internet-service search engines to find exploitable services.
  - Some attackers avoid IANA-assigned protocols, causing misclassification of at least 15% of traffic on some ports.
- Provides recommendations for researchers and operators based on findings.

**5. LZR: Identifying Unexpected Internet Services**  
_Stanford University paper artifacts_
- Focuses on Internet-wide scanning and services on non-standard ports.
- Studies where Internet services are actually deployed in practice.
- Evaluates security posture of services on unexpected (non-IANA) ports.
- Shows protocol deployment is more diffuse than commonly assumed.
- Demonstrates that many protocols run on numerous ports beyond their primary IANA-assigned port, e.g.:
  - Only ~3% of HTTP services on port 80.
  - Only ~6% of TLS services on port 443.
- Finds services on non-standard ports are more likely to be insecure.
- Concludes that prior studies significantly underestimate the true security posture of Internet hosts when focusing only on standard ports.

---

### Pricing
- Not specified on the provided content. Data is explicitly restricted to **non-commercial use**, but no fee structure or paid plans are described.

---

### Access / Integration
- Programmatic access via JSON interface at `/json` (no further technical details provided in the content).