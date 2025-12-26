# fucking-quick-look-plugins

**Category:** Themed Directories  
**Tags:** macOS, developer-tools, awesome-lists  
**Source:** https://github.com/Correia-jpv/fucking-quick-look-plugins

## Overview
`fucking-quick-look-plugins` is an awesome-style curated list of useful macOS Quick Look plugins focused on developer workflows. It aggregates plugins, their purposes, and GitHub popularity (stars and forks) to help developers quickly find and install Quick Look extensions that improve file previews in Finder.

## Features
- Curated **awesome-style list** of Quick Look plugins specifically for **developers**.
- Focus on **macOS Quick Look enhancements** to improve file previews directly in Finder.
- Each plugin entry includes:
  - Brief description of what the plugin previews/enhances.
  - GitHub **star** and **fork** counts (when available).
  - Links to plugin **repositories** and/or **download pages**.
  - **Homebrew** installation commands when available.
  - Manual download links as an alternative to Homebrew.
- Includes **installation instructions** for:
  - Installing via **Homebrew** (`brew install <package>` or `brew install --cask <package>`).
  - **Manual installation** by placing plugins in `~/Library/QuickLook` and running `qlmanage -r` to reload Quick Look.
- Provides **macOS Catalina and later notes**:
  - Shows how to inspect extended attributes on Quick Look plugins with `xattr -r ~/Library/QuickLook`.
  - Explains how to remove macOS quarantine attributes to get plugins working: `xattr -d -r com.apple.quarantine ~/Library/QuickLook`.
- Contains **screenshots** for some plugins to show how previews look in Finder.

### Example Plugins Listed
From the visible portion of the content (the list is longer in the repository):

- **QLStephen**  
  - Purpose: Preview plain text files without or with unknown file extensions (e.g., `README`, `CHANGELOG`, `index.styl`).  
  - Install: `brew install qlstephen` or download from GitHub releases.  
  - Extras: Screenshot included.

- **QLMarkdown**  
  - Purpose: Preview Markdown (`.md`) files.  
  - Install: `brew install --cask qlmarkdown` or download from GitHub releases.  
  - Extras: Screenshot included.

- **QuickLookJSON**  
  - Purpose: Preview JSON files.  
  - Install: `brew install quicklook-json` or download from the project website.

> Note: The full repository likely lists many more Quick Look plugins with similar structure (description, stars/forks, install methods).

## Usage
- Browse the list to find Quick Look plugins relevant to your development workflow (e.g., Markdown, JSON, text, code, config formats).
- Install desired plugins via **Homebrew** or manual download.
- Place manually downloaded `.qlgenerator` plugins into `~/Library/QuickLook` and run `qlmanage -r` to refresh Quick Look.
- On newer macOS versions (e.g., Catalina+), remove quarantine attributes if plugins don’t load.

## Pricing
- The project itself is an **open-source, free GitHub repository** that curates links to various third-party Quick Look plugins.  
- Individual plugins linked may have their own licenses, but from the provided content there are **no paid plans or pricing tiers** mentioned.