# Git Tips

A curated collection of concise Git tips and command examples, maintained as an open-source repository.

**Website:** https://github.com/git-tips/tips#readme  
**Category:** Themed directories  
**Tags:** git, developer-tools, tips  
**Source:** GitHub

---

## Overview
Git Tips is a repository of practical Git commands and patterns, organized as small, copyable snippets. It focuses on everyday workflows (branching, history inspection, reset/revert, cleanup, etc.) and serves as a quick reference for developers using Git from the command line.

The collection is community-driven and available in multiple languages.

---

## Features

### 1. Tip Collection & Coverage
A wide range of Git workflows and use cases are covered, including (but not limited to):

- **Everyday workflows**
  - "Everyday Git in twenty commands or so" – a compact set of commands for routine daily Git usage.

- **Help & documentation**
  - Show built‑in Git guides and documentation.

- **Searching & history inspection**
  - Search changes by content.
  - Show changes over time for a specific file.
  - List of all files up to a specific commit.
  - List of all files changed in a given commit.
  - View unstaged changes since the last commit.
  - View changes staged for commit.
  - Show both staged and unstaged changes.
  - See commit history for just the current branch.
  - See all commits made since forking from `master` (listed in the index).

- **Cleaning & rewriting history**
  - Remove sensitive data from history after it has been pushed.
  - Git reset of the first commit.
  - Reset while preserving uncommitted local changes.
  - Reset to discard commits (recommended for private branches).
  - Undo local changes with the last content in `HEAD`.
  - Revert a commit by creating a new commit.

- **Branch management**
  - List all conflicted files (useful during merges).
  - List all branches already merged into `master`.
  - Quickly switch to the previous branch.
  - Remove branches that have already been merged into `master`.
  - List all branches with their upstreams and the last commit on each branch.
  - Track an upstream branch.
  - Get list of all local and remote branches.
  - Get only remote branches.
  - Delete a local branch.
  - Delete a remote branch.

- **Tag management**
  - Create a local tag.
  - Delete a local tag.
  - Delete a remote tag.

- **Remote repositories**
  - Change a remote’s URL.
  - Get list of all remote references.

- **Authorship & metadata**
  - Reword the previous commit message.
  - Amend the author of a commit.
  - Reset author info after global config author has changed.

- **Index and staging**
  - Stage parts of a changed file instead of the entire file (interactive staging).

- **Shell integration & quality of life**
  - Enable Git bash completion.
  - Show what changed since a given time period (e.g., "since two weeks").

> Note: All commands in the repository are tested on `git version 2.7.4 (Apple Git-66)` (as stated in the content), but most are applicable to modern Git versions.

### 2. Multi-language Availability
Git Tips is available in several languages via community-maintained mirrors:

- English
- 中文 (Chinese)
- Русский (Russian)
- 한국어 (Korean)
- Tiếng Việt (Vietnamese)
- 日本語 (Japanese)
- नेपाली (Nepali)
- Polski (Polish)
- فارسی (Persian)

Each language typically has its own GitHub repository linked from the main README.

### 3. Tooling

- **git-tip CLI**  
  - A command-line tool (`git-tip` on npm) to access and use the tips from the terminal.
  - Available as a **Docker container** for easy usage without local installation of the NPM package.

### 4. Contribution

- Public, open-source repository on GitHub.
- Contributions are accepted through a documented process (`contributing.md`), allowing users to add and refine tips.

---

## Pricing

Git Tips is an open-source, GitHub-hosted resource.  
**Price:** Free (no paid plans or pricing tiers indicated).

---

## Tech & Platform

- **Platform:** GitHub repository.
- **Primary interface:** Markdown documentation and command-line examples.
- **Related ecosystem tools:** `git-tip` NPM package, optional Docker image.
