# Awesome Honeypots

**Category:** Themed Directories  
**Website:** https://github.com/paralax/awesome-honeypots#readme  
**Platform:** GitHub

A curated, community-maintained directory of honeypot resources and related security tooling, with a particular focus on free and open-source projects.

---

## Overview

Awesome Honeypots is an "awesome list" that aggregates links to honeypots and supporting tools used to study, detect, and deceive attackers. Items are grouped into themed categories (e.g., web, services, ICS/SCADA), making it easier to find relevant tools for building and operating honeypot and honeynet environments.

---

## Features

### Curated Honeypot Directory
- Collection of honeypot implementations and related tools.
- Focus on free and open-source projects.
- Items organized into logical categories for easier navigation.

### Honeypot Categories
- **Database Honeypots** – Tools emulating database services to detect and study database-focused attacks.
- **Web Honeypots** – Honeypots imitating web applications or HTTP services.
- **Service Honeypots** – General network/service honeypots covering various protocols and services.
- **Distributed Honeypots** – Frameworks and platforms for deploying and managing honeypots across multiple sensors/locations.
- **ICS/SCADA Honeypots** – Honeypots tailored to industrial control systems and SCADA environments.
- **Other / Random Honeypots** – Miscellaneous or specialized honeypots not fitting standard categories.
- **SSH Honeypots** – Tools focused on SSH-based attack detection and credential capture.
- **Client Honeypots** – Client-side honeypots that actively interact with potentially malicious servers or content.
- **Hybrid Low/High Interaction Honeypots** – Solutions combining lightweight emulation with deeper interaction capabilities.

### Supporting and Related Tools
The list also includes tools that complement honeypot deployments, such as:
- **Botnet C2 tools** – For studying or emulating command-and-control behavior.
- **IPv6 attack detection tools** – Focused on analyzing or detecting IPv6-related attacks.
- **Dynamic code instrumentation toolkits** – For instrumenting binaries or applications during analysis.
- **Website-to-honeypot converters** – Tools to convert an existing website into a server honeypot.
- **Malware collectors** – Automated collection of malicious artifacts, often integrated with honeypots.
- **Distributed sensor deployment frameworks** – Systems for rolling out honeypot sensors at scale.
- **Network analysis tools** – For examining traffic collected from honeypots.
- **Log anonymizers** – To sanitize and share captured data while protecting sensitive information.
- **Low-interaction router/backdoor honeypots** – Simulated routers or embedded devices to observe scanning and exploitation.
- **Honeynet farm traffic redirectors / network traffic redirectors** – To direct suspicious or targeted traffic into honeynet environments.
- **HTTPS proxies** – For intercepting and inspecting encrypted traffic related to attacks.
- **System instrumentation utilities** – For monitoring host behavior and system-level events.
- **USB-spreading malware honeypots** – Focused on malware that propagates via USB or removable media.
- **Data collection frameworks** – For aggregating and storing data from honeypots or sensors.
- **Passive network audit parsers** – For parsing and analyzing passive capture/audit data.
- **VM monitoring and tooling** – For supervising virtualized environments running honeypots or malware.
- **Binary debuggers** – Used in analysis of captured malware or exploit behavior.
- **Mobile analysis tools** – For attacks and malware targeting mobile platforms.
- **Honeynet data fusion utilities** – To correlate and combine honeypot data from multiple sources.
- **Servers / infrastructure components** – Supporting backend services for honeypot ecosystems.
- **IDS signature generation tools** – To create intrusion detection rules from observed malicious behavior.
- **AS-number and prefix lookup services** – For enrichment of network data (e.g., attacker IP context).
- **Data collection / data sharing platforms** – For exchanging honeypot-derived data.
- **Central management tools** – For orchestrating and configuring multiple honeypots.
- **Network connection analyzers** – Inspect and categorize captured connections.
- **Honeypot deployment tools** – Assist with provisioning and automated setup.
- **Wireshark honeypot extensions** – Add-ons or plugins to enhance packet analysis in honeypot contexts.
- **PCAP analyzers** – For deeper investigation of recorded network traces.
- **PDF document inspectors** – Tools for analyzing potentially malicious PDF files.
- **Honeypot distributions with mixed components** – Pre-built operating system or appliance images combining multiple honeypots and tools.

### Community & Contributions
- Open contribution model via GitHub.
- Contribution guidelines provided in `CONTRIBUTING.md`.
- Available in multiple languages (e.g., `README.md` and `README_CN.md`).
- Uses an "awesome"-style structure, consistent with other lists in the sindresorhus/awesome ecosystem.

### Licensing & Repository Structure
- Explicit license file (`LICENSE`).
- Automated checks (`awesome-check.py`) to maintain list quality and formatting.

---

## Pricing

- Not a commercial product or service.  
- The list and linked open-source projects are generally free to access and use, subject to their individual licenses.

---

## Tags

- awesome-lists  
- security  
- honeypots