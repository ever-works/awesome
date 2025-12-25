# Awesome Swift Playgrounds

A curated directory of Swift Playgrounds for learning, experimenting, and exploring the Swift language and related technologies.

---

## Overview

**Type:** Themed directory / curated list  
**Focus:** Swift Playgrounds for education, experimentation, and demos  
**Primary Platform:** Xcode Playgrounds & Swift PlaygroundBooks (iPad)

This repository collects numerous Swift playgrounds, organized by topic and format, including student submissions for WWDC scholarships, learning resources for Swift (from beginner to advanced), and domain-specific examples in graphics, audio, math, and more.

---

## Features

### General
- Curated list of Swift playgrounds from multiple authors and repositories.
- Emphasis on educational and exploratory use of Swift.
- Most playgrounds indicated as compatible with Swift 3; some tagged for Swift 4+ or older (pre-Swift 3).
- Includes both standard Xcode playgrounds and PlaygroundBooks that run on iPad.
- Tagging system for quick reference:
  - 🌟: Maintainer’s personal favorites
  - 🍁: Swift 4+ playgrounds
  - ⏳: Pre-Swift 3 playgrounds

### Organization & Categories
Playgrounds are grouped into themed sections:

1. **WWDC Students Submissions**
   - Collections of playgrounds submitted for the WWDC scholarship across multiple years:
     - 2014, 2015, 2016, 2017, 2018, 2019, 2020, 2021, 2022 (and more as listed).
   - Each year links to a dedicated GitHub repository containing that year’s student submissions.

2. **PlaygroundBooks (iPad-ready)**
   Playgrounds specifically packaged as PlaygroundBooks, runnable on iPad:
   - **Guilloche Pattern Playground Book**  
     Learn about guilloche patterns—complex, carefully designed line patterns commonly seen in everyday life (e.g., security printing). 🍁
   - **Accessibility**  
     PlaygroundBook focused on accessibility concepts for iOS developers. 🍁
   - **TJBot Playground**  
     Swift Playground for interacting with IBM’s TJBot hardware/robot. 🍁
   - **Tree Trouble Playbook**  
     Interactive PlaygroundBook about Binary Search Trees.
   - **Auto Pong**  
     Tutorial-style playground that guides you through implementing a Pong-style game based on a simple AI.
   - **Neural Network Playground**  
     Swift playground demonstrating neural networks without third‑party dependencies.
   - **Window Manager Playground**  
     Experimental window manager playground (PlaygroundBook format).

3. **Learning Swift**
   - Playgrounds aimed at learning Swift fundamentals (syntax, language basics, standard library usage).  
   *(Full list in the original repository; summarized category only here.)*

4. **Learning Swift: Advanced Topics**
   Subsections for more advanced Swift concepts:
   - **Design Patterns** – Playgrounds that demonstrate common software design patterns in Swift.
   - **Protocol Oriented Programming** – Examples focused on protocol-centric design in Swift.
   - **Functional Reactive Programming** – Playgrounds exploring FRP concepts and libraries in Swift.

5. **Apple's Playgrounds**
   - Official Apple-created Swift playgrounds (often distributed as ZIP archives, downloaded separately).

6. **Playgrounds about Playgrounds**
   - Meta-playgrounds that teach or demonstrate how to build or extend Swift Playgrounds themselves.

7. **Playgrounds from Playgroundbooks**
   - Standalone playgrounds derived from or associated with existing PlaygroundBooks.

8. **Theoretical Computer Science**
   - **Algorithms and Data Structures** – Implementations and visualizations of classic algorithms and data structures.
   - **Languages** – Playgrounds exploring programming language concepts (parsers, interpreters, etc.).
   - **Machine Learning** – ML-related examples and experiments implemented as Swift playgrounds.

9. **UIKit and Graphics**
   Visual and UI-focused playgrounds, with subcategories:
   - **Core Image** – Image processing and filter examples.
   - **Metal** – GPU-based graphics and compute demos using Metal.
   - **Animations** – UIKit or Core Animation-based motion/animation demos.
   - **SpriteKit** – 2D game and sprite-based demos using SpriteKit.

10. **Audio**
    - Audio synthesis, playback, and processing examples in Swift playgrounds.

11. **Mathematics**
    - Math-focused explorations: numerical methods, visualizations, and math demos.

12. **Libraries and APIs**
    - Playgrounds that demonstrate usage of third-party libraries or external APIs.

13. **Playground Sets**
    - Bundles or series of related playgrounds covering a specific topic or course-like progression.

14. **Miscellaneous**
    - Playgrounds that don’t fit neatly into other categories but demonstrate interesting ideas or techniques.

### Download & Usage
- All playgrounds included as Git submodules under the `playgrounds/` directory.
- Bulk download options:
  - `git clone --recursive https://github.com/uraimo/Awesome-Swift-Playgrounds.git`
  - Or clone normally, then run: `git submodule update --init`
- Apple-provided playgrounds distributed as ZIP files must be downloaded manually from their respective sources.

### Contribution Workflow
- Public contribution guidelines provided in `CONTRIBUTING.md`.
- Community-driven updates: users are encouraged to submit pull requests to:
  - Add new relevant playgrounds.
  - Remove or update playgrounds that no longer work with current Xcode.
  - Improve categorization and documentation.

---

## Pricing

- Not applicable. This is an open, curated list of third‑party Swift playgrounds hosted on GitHub; no pricing or paid plans are defined in the provided content.

---

## Links

- **Directory home / README:** https://github.com/uraimo/Awesome-Swift-Playgrounds#readme
- **Contribution guidelines:** https://github.com/uraimo/awesome-swift-playgrounds/blob/master/CONTRIBUTING.md
- **WWDC submissions overview:** Linked per year within the "WWDC Students Submissions" section in the README.