# Vim Galore – Awesome Vim

**URL:** https://github.com/mhinz/vim-galore#readme
**Category:** Themed Directories  
**Tags:** editor, vim, developer-tools

## Overview
Vim Galore is an extensive, curated compendium of Vim tips, tricks, explanations, and resources. It functions as a structured reference and learning guide for Vim users of all levels, covering everything from fundamentals to advanced usage, debugging, and workflow optimization.

## Features

### Intro & Fundamentals
- Explanation of what Vim is and its core concepts
- Discussion of the Vim philosophy and modal editing
- First steps for new Vim users
- Example **minimal `vimrc`** configuration
- How to determine **what kind of Vim** you are running (build, features, variants)
- Links and references to **cheatsheets** for quick lookup

### Basics (Core Editing Concepts)
- **Buffers, windows, tabs**: structure of open files and views
- **Active, loaded, listed, named buffers**: buffer states and management
- **Argument list**: working with multiple files from the command line or within Vim
- **Mappings**: defining custom key mappings
- **`mapleader`**: leader key concept and usage for custom shortcuts
- **Registers**: yanks, deletes, and named registers
- **Ranges**: specifying line ranges for commands
- **Marks**: bookmarking positions in files
- **Completion**: built-in completion methods and usage
- **Motions, operators, text objects**: composable editing commands
- **Autocmds**: automatic commands triggered by events
- **Changelist, jumplist**: navigating through editing and jump history
- **Undo tree**: branching undo history and how to navigate it
- **Quickfix and location lists**: handling search results, compiler output, and diagnostics
- **Macros**: recording and replaying command sequences
- **Colorschemes**: configuring and switching color themes
- **Folding**: code and text folding methods
- **Sessions**: saving and restoring editing sessions
- **Locality**: concepts and practices for localized configuration and behavior

### Usage & Workflow
- **Getting help offline** via Vim’s built-in `:help`
- **Alternative offline help** methods
- **Getting help online**: useful remote documentation sources
- **Autocmds in practice** with:
  - User-defined events
  - Nested autocommands
- **Clipboard integration**:
  - Clipboard usage on Windows and macOS
  - Clipboard usage on Linux, BSD, and similar systems
- **Restore cursor position** automatically when reopening files
- **Temporary files management**:
  - Backup files
  - Swap files
  - Undo files
  - `viminfo` files
  - Example configurations for handling these temporary files
- **Editing remote files** (e.g., via netrw or other methods)
- **Managing plugins**: strategies and tools for plugin management
- **Block insert**: visual block editing techniques
- **Running external programs and filters** from within Vim
- **Cscope integration** for code navigation
- **MatchIt** usage for improved matching of code constructs
- **True color support**: enabling and using 24-bit color in Vim

### Tips & Enhancements
Practical, focused tips to refine everyday editing:
- Go to the **other end of selected text** quickly
- **Saner behavior of `n` and `N`** in search navigation
- **Improved command-line history** handling
- **Saner `CTRL-L`** behavior
- Disable **audible and visual bells**
- **Quickly move the current line** up or down
- **Quickly add empty lines** around text
- **Quickly edit your macros**
- **Quickly jump between header and source files**
- **Quickly change font size** in GUI versions of Vim
- Change **cursor style by mode** (normal/insert/etc.)
- **Preserve selection** when shifting text sideways
- **Reload a file on saving** under certain workflows
- **Smarter `cursorline`** behavior
- **Faster keyword completion** through configuration tweaks
- **Cosmetic changes to colorschemes** without fully rewriting them

### Commands & Scripting
- **`:global` and `:vglobal`**: execute commands on all lines matching (or not matching) a pattern
- **`:normal` and `:execute`**: combining normal-mode commands with scripting for automation
- **`:redir` and `execute()`**: capturing command output programmatically

### Debugging & Performance
- **General debugging tips** for Vim configuration and runtime issues
- **Verbosity** settings and techniques to gain insight into what Vim is doing
- **Profiling startup time** to optimize `.vimrc` and plugin load
- **Profiling at runtime** to identify slow operations or scripts

## Pricing
Vim Galore is an open GitHub repository and reference resource; no pricing or paid plans are indicated.