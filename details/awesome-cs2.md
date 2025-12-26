# awesome-cs2

**Category:** Themed Directories  
**Tags:** awesome-lists, games, mods

## Overview
awesome-cs2 is a curated “awesome list” of Counter-Strike 2 (CS2) development resources. It focuses on tools, frameworks, documentation, and plugins for modding and developing within the CS2 / Source 2 ecosystem.

- **Type:** Open-source, curated directory (GitHub repository)
- **Scope:** CS2 modding, development tools, documentation, and related resources
- **Maintainer/Brand:** samyycX
- **Repository:** https://github.com/samyycX/awesome-cs2
- **Last Sync (from repo):** 2025/12/25 02:11:00
- **Project Uptime:** 4 months

## Features

### Directory Structure & Data
- **Organized data and manifests**
  - `data/` folder containing structured resource entries
  - `manifests/` folder for managing or versioning resource lists
  - `contributors.json` listing contributors
  - `current.tag` indicating current sync/version tag
- **Generator tooling**
  - `generator/` directory for scripts or tools that build or update the awesome list from raw data
- **Templates & Documentation**
  - `README.md` with main list content
  - `TEMPLATE.md` to standardize how new entries are added
  - GitHub workflows under `.github/workflows` for automated generation/CI tasks

### Covered Resource Areas

#### General CS2 / Source 2 Information
- **Source2 Wiki** (https://source2.wiki)
  - Actively maintained Source 2 wiki
  - Information on workshop tools and entities
- **cs2browser.net** (https://cs2browser.net)
  - Live CS2 community server browser
  - Filters out fake servers and advertisements
- **Valve Official Documentation** (https://developer.valvesoftware.com/)
  - Official Valve documentation for CS2 and other Source games
  - Noted as often outdated or lacking for CS2-specific information
- **gamebanana CS2 Section** (https://gamebanana.com/games/18134)
  - Repository of CS2 workshop content
  - Includes models, maps, and other mod resources

#### Tools
- **Source2Viewer** (https://s2v.app/)
  - Tool to unpack resources from VPK files
  - Supports decompiling content from VPK archives
- **VPulse Editor** (https://github.com/LionDoge/vpulse-editor)
  - Visual programming editor for VPulse scripts
  - Targets Source 2’s upcoming visualized script system intended to replace VScript
- **Source2 Schema Dumper** (https://github.com/GAMMACASE/Source2SchemaDumper)
  - Metamod plugin for dumping schema data from game binaries
  - Can generate C/C++ header files
  - Headers can be imported into IDA for reverse engineering workflows
- **DepotDownloader** (https://github.com/SteamRE/DepotDownloader)
  - Command-line tool to download game depots/files of specific versions
  - Useful for obtaining particular CS2 builds or assets
- **PltPatcher** (https://github.com/GAMMACASE/PltPatcher)
  - IDA Python plugin
  - Patches PLT sections when IDA fails to handle them correctly
  - Assists in more accurate binary analysis

## Use Cases
- Discovering documentation and wikis relevant to CS2 modding and development
- Finding tools for unpacking, decompiling, and analyzing CS2/Source 2 assets
- Working with game binaries for schema extraction and reverse engineering
- Accessing community resources like models, maps, and server listings
- Using a maintained, awesome-list-style index instead of ad-hoc search

## Pricing
- The directory itself and all referenced tools/resources listed are open-source or freely accessible as described in the repository.  
- No pricing plans are defined within the provided content.
