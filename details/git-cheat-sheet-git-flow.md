# Git Cheat Sheet & Git Flow

A comprehensive Git cheat sheet repository that documents commonly used Git commands and Git Flow practices, designed as a quick reference for developers at any level.

---

## Overview

- **Name:** Git Cheat Sheet & Git Flow
- **Type:** Open-source reference / documentation
- **Category:** Themed Directories
- **Source:** [GitHub Repository](https://github.com/arslanbilal/git-cheat-sheet#readme)
- **Brand:** GitHub
- **Tags:** git, developer-tools, documentation

---

## Features

### General
- Concise, command-focused Git reference.
- Suitable for both beginners and experienced developers.
- Organized by common workflows and tasks.
- Community-driven with contributions encouraged (e.g., new commands, translations, explanation improvements).

### Coverage & Structure
- **Setup**
  - View current Git configuration: `git config --list`
  - View repository configuration: `git config --local --list`
  - View global configuration: `git config --global --list`
  - View system configuration: `git config --system --list`
- **User Configuration**
  - Set global user name: `git config --global user.name "[firstname lastname]"`
  - Set global user email: `git config --global user.email "[valid-email]"`
- **Display & Editor Settings**
  - Enable automatic command line coloring: `git config --global color.ui auto`
  - Set global editor for commits: `git config --global core.editor vi`

### Configuration Files
- Lists Git configuration scopes and locations:
  - **Repository scope**: `<repo>/.git/config` (`--local`)
  - **User scope**: `~/.gitconfig` (`--global`)
  - **System scope**: `/etc/gitconfig` (`--system`)

### Repository Management
- **Create / Clone Repositories**
  - Clone via SSH: `git clone ssh://user@domain.com/repo.git`
  - Clone via HTTPS: `git clone https://domain.com/user/repo.git`
  - Initialize repository in current directory: `git init`
  - Initialize repository in a specific directory: `git init <directory>`

### Local Changes
- **Check Status & Differences**
  - Show repository status: `git status`
  - Show changes to tracked files: `git diff`
  - Show changes for a specific file: `git diff <file>`
- **Staging Changes**
  - Add all changes: `git add .`
  - Add specific files: `git add <filename1> <filename2>`
  - Interactively stage hunks: `git add -p <file>`
- **Committing Changes**
  - Commit all tracked file changes: `git commit -a`
  - Commit staged changes: `git commit`
  - Commit with message: `git commit -m 'message here'`
  - Skip explicit staging and commit with message: `git commit -am 'message here'`
  - Commit with specific date: `git commit --date="`date --date='n day ago'`" -am "<Commit Message Here>"`
- **Modify Last Commit**
  - Amend the last commit: `git commit --amend` (with warning about not amending published commits).

### Git Flow & Additional Topics
- Includes sections (in the table of contents) for:
  - Search
  - Commit history
  - Move / rename operations
  - Branches & tags
  - Update & publish (pushing, pulling, fetching, etc.)
  - Merge & rebase
  - Undo operations
  - Git Flow usage
  - Other languages (translations of the cheat sheet)

*(Note: only part of the content is shown; the actual repository includes more detailed commands under each section.)*

---

## Pricing

- No pricing information is provided. The resource is a public GitHub repository and appears to be free to use as a cheat sheet.

---

## Links

- **Repository / Documentation:** https://github.com/arslanbilal/git-cheat-sheet#readme
- **Brand Logo:** https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
