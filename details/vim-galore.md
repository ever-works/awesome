# Vim Galore

**Website:** https://github.com/mhinz/vim-galore  
**Category:** Themed Directories  
**Topic:** Vim editor tips, tricks, and resources  
**License:** CC BY-SA 4.0

## Overview
Vim Galore is a comprehensive, curated collection of documentation, tips, workflows, and external links for learning and mastering Vim. It is organized as a single, extensive guide covering both fundamental concepts and advanced usage, with translations available in multiple languages.

## Features

### General Structure
- Extensive README-based guide organized by topic with a detailed table of contents.
- Focus on explaining Vim concepts, configuration, and practical usage patterns.
- Links to external resources (cheatsheets, plugins, articles, translations).
- Additional documents such as `PLUGINS.md`, `CONTRIBUTING.md`, and `CODE_OF_CONDUCT.md`.
- Available translations: Chinese, Japanese, Portuguese, Russian, Vietnamese (linked from the repository).

### Core Vim Concepts and Basics
- **What is Vim?**
  - Explanation of Vim’s role as a modal text editor and its typical use cases.
- **The Vim Philosophy**
  - Overview of modal editing, composability of commands, and efficiency-focused workflow.
- **First steps**
  - Guidance for beginners on getting started with Vim.
  - Introductory operations, navigation, and basic editing.
- **Minimal vimrc**
  - Example of a minimal configuration file.
  - Core options and sensible defaults to start from.
- **What kind of Vim am I running?**
  - How to inspect your Vim build, version, and enabled features.
- **Cheatsheets**
  - References to Vim keybinding and command cheatsheets.

### Editing Model and Data Structures
- **Buffers, windows, tabs**
  - Explanation of the differences between buffers, windows, and tabs.
  - Best practices for working with multiple files and views.
- **Active, loaded, listed, named buffers**
  - Clarification of buffer states and how they affect navigation and commands.
- **Argument list**
  - Use of the argument list for working with sets of files.
- **Changelist, jumplist**
  - How Vim records movements and changes and how to navigate them.
- **Undo tree**
  - Understanding Vim’s undo branches and how to move through them.
- **Quickfix and location lists**
  - Use cases for search and compilation results.
  - Navigation patterns and commands.

### Configuration and Customization
- **Mappings**
  - Explanation of key mappings, normal/insert/visual mode mappings.
  - Best practices and gotchas.
- **Mapleader**
  - Purpose of `<Leader>`.
  - How to set and use a custom leader key.
- **Registers**
  - Types of registers (unnamed, numbered, named, special).
  - How to read from and write to registers.
- **Ranges**
  - Syntax for specifying line and text ranges in commands.
- **Marks**
  - Setting marks, global vs local marks, and navigating via marks.
- **Colorschemes**
  - How to install, select, and manage color schemes.
- **Folding**
  - Fold methods (manual, indent, syntax, etc.) and workflow.
- **Sessions**
  - Saving and restoring editing sessions (open files, windows, options).
- **Locality**
  - Explains local buffer/window/tab options versus global ones, and how scope affects behavior.

### Text Manipulation and Navigation
- **Completion**
  - Built-in completion options in Insert mode.
  - Configuration and usage patterns.
- **Motions, operators, text objects**
  - Core motion commands.
  - Operator-pending commands and how to combine them.
  - Use of text objects for structured editing.
- **Macros**
  - Recording, storing, and replaying macros for repetitive tasks.

### Automation and Events
- **Autocmds**
  - Concept of autocommands and events in Vim.
  - How to define and organize autocmds.
- **Autocmds in practice**
  - Practical examples of using autocmds to automate workflows.
  - Explanation of common event types.
  - **User events**: defining and using custom user autocmd events.
  - **Nested autocmds**: how nested autocommands behave and how to control them.

### System Integration and Clipboard
- **Clipboard**
  - How Vim interacts with the system clipboard.
  - **Clipboard usage (Windows, macOS)**: platform-specific guidance on yanking and pasting between Vim and other applications.

### Help and Learning Resources
- **Getting help offline**
  - Using Vim’s built-in `:help` system.
  - Navigating help topics and related documentation.
- **Getting help offline (alternative)**
  - Additional offline-accessible documentation approaches.
- **Getting help online**
  - Links and methods for finding Vim help on the web (wikis, Q&A, etc.).

### Plugins and Ecosystem
- `PLUGINS.md` (separate file) listing and describing Vim plugins and plugin-management practices (categories, recommended tools, and ecosystem overview).

## Pricing
Not applicable. Vim Galore is a freely available open-source documentation resource licensed under CC BY-SA 4.0.

## Tags
- vim
- editor
- resources
- tips
- documentation
- learning
- open-source
