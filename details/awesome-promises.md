# Awesome Promises

**Website:** https://github.com/wbinnssmith/awesome-promises#readme  
**Category:** Themed Directories  
**Tags:** JavaScript, async, developer-tools

## Overview
Awesome Promises is a curated, community-driven directory of resources, libraries, and tools for working with JavaScript Promises. It is part of the broader "Awesome" collection of developer-focused lists.

## Features

### Curated Learning Resources
- **Resources, Blogs, and Books** focused on JavaScript Promises.
- Sections for different experience levels:
  - **For beginners** – introductory materials to understand Promises.
  - **Deep Dive** – advanced and in-depth articles or materials.
  - **References** – reference-style documentation and guides.

### Library & Implementation Directory
- **Promises/A+ Implementations (ES6/ES2015 compatible)**
  - **Strict Implementations**
    - Implement no more or less than the ES6 Promise specification.
    - Intended as polyfills and highly compatible with native promises.
  - **Implementations with extras**
    - Promise libraries that extend standard behavior while remaining compatible.
    - Designed for both Node.js and browser environments.
    - Example helper methods/utilities mentioned:
      - `nodeify`
      - `denodify`
      - `done()`
  - **Fallbacks**
    - Lightweight Promise-like utilities for environments lacking full support.
    - Example: `pinkie`.

### Convenience Utilities for Promises
- Focus on small, focused modules that enhance native or spec-compliant Promises.
- **sindresorhus’s Promise utilities** (grouped as “promise-fun”):
  - Enhancements and helpers around:
    - `.then()`
    - `.catch()`
    - `Promise.race()`
    - `Promise#try()`
    - `Promise#finally()`
    - `Promise.all()`
    - Working with `Map` and `Object` in async contexts.
- **Other Promise utilities and patterns**:
  - `bluebird.method`
  - `bluebird.coroutine`
  - `task.js`
  - `nodeify`

### Open Contribution & Repository Structure
- Hosted on GitHub as a public repository.
- Includes:
  - `README.md` – main curated list and documentation.
  - `CONTRIBUTING` – guidelines for contributing new items and improvements.
  - `.editorconfig` – consistent coding/text editor settings.
  - `.travis.yml` – continuous integration configuration.
  - `LICENSE` – license information.

### Licensing
- Content licensed under **Creative Commons CC0** (public domain dedication).
- Allows reuse, modification, and redistribution with minimal restrictions.

## Pricing
- Awesome Promises is a free, open-source resource with no pricing or paid plans.