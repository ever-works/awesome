# Quick Look Plugins

Awesome-curated directory of Quick Look plugins for macOS, focused on tools that extend the native Quick Look preview for developers and power users.

---

## Overview

- **Type:** Themed directory / curated list
- **Platform:** macOS (Quick Look plugins)
- **Use case:** Enhance Finder’s Quick Look to preview more file types and get richer previews useful for development and technical workflows.

---

## Installation

### Using Homebrew

General pattern:

```bash
brew install <package>
```

For specific plugins (from content provided):

- **QLStephen**
  ```bash
  brew install qlstephen
  ```
- **QLMarkdown**
  ```bash
  brew install --cask qlmarkdown
  ```
- **QuickLookJSON**
  ```bash
  brew install quicklook-json
  ```
- **BetterZip (includes BetterZipQL plugin)**
  ```bash
  brew install betterzip
  ```

#### Catalina and later (quarantine attribute)

To inspect quarantine attributes:

```bash
xattr -r ~/Library/QuickLook
```

To remove the quarantine attribute so plugins work correctly:

```bash
xattr -d -r com.apple.quarantine ~/Library/QuickLook
```

### Manual Installation

- Place plugin files in:
  ```
  ~/Library/QuickLook
  ```
- Then refresh Quick Look:
  ```bash
  qlmanage -r
  ```

---

## Features

### General Directory Features

- Curated list of Quick Look plugins oriented toward developers.
- Direct links to each plugin’s homepage or repository.
- Installation instructions per plugin (Homebrew and manual download where available).
- Screenshots for many plugins to show preview behavior.

### Individual Plugins (from provided content)

#### QLStephen

- **Purpose:** Preview plain text files that have no extension or an unknown extension.
- **Examples:** README, CHANGELOG, `index.styl`, and other text-based files.
- **Integration:** Appears in Finder’s Quick Look.
- **Install:**
  - `brew install qlstephen`
  - Or download the latest release manually from GitHub.

#### QLMarkdown

- **Purpose:** Render and preview Markdown (`.md` and related) files via Quick Look.
- **Install:**
  - `brew install --cask qlmarkdown`
  - Or download the latest release manually from GitHub.

#### QuickLookJSON

- **Purpose:** Preview JSON files in Quick Look, typically with formatting suited to structured data.
- **Install:**
  - `brew install quicklook-json`
  - Or download the plugin as a `.qlgenerator` ZIP from the developer’s site.

#### BetterZipQL (via BetterZip)

- **Purpose:** Preview archive contents (e.g., ZIP and other archive formats) directly in Quick Look.
- **Current distribution:**
  - The BetterZipQL plugin is now integrated into the **BetterZip** application.
- **Install:**
  - `brew install betterzip` to get the app and its Quick Look plugin.
  - Or download the BetterZip app manually.
- **Legacy plugin:**
  - A standalone legacy BetterZipQL plugin is still available as a separate download.

---

## Pricing

- The repository itself is **free and open-source**.
- Plugins listed may have their own licensing or pricing; the provided content does not list specific prices or plans.
