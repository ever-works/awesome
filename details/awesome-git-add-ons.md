# Awesome Git Add-ons

**Category:** Themed Directories  
**Brand:** GitHub  
**Website:** https://github.com/stevemao/awesome-git-addons#readme

A curated directory of add-ons and extensions that extend and enhance the Git command-line interface. The list aggregates many third‑party tools to improve workflows around branching, history inspection, collaboration, statistics, and more.

> Note: Some listed commands may require post‑install scripts or manual alias configuration before they work.

---

## Features

### General
- Curated list focused specifically on Git CLI extensions.
- Organised table of contents covering a wide range of tools and use‑cases.
- Includes notes where certain commands may need extra setup (post-install scripts, alias configuration).

### Example Listed Add-ons

#### git-extras
A collection of useful Git utilities that add higher‑level commands.

Key commands shown in the content include:

- **`git squash`**  
  - Squash multiple commits into a single one, by branch name, commit hash, or relative reference.  
  - Example usage:
    - `git squash fixed-cursor-styling "Fixed cursor styling"`
    - `git squash 95b7c52`
    - `git squash HEAD~3`

- **`git summary`**  
  - Display a high‑level summary of the repository, including:
    - Project name
    - Repository age
    - Number of active days
    - Total commits
    - Number of files
    - Author list with commit counts and percentages
  - Example output:
    - `project  : git`
    - `repo age : 10 years`
    - `active   : 11868 days`
    - `commits  : 40530`
    - `files    : 2825`
    - `authors  :` followed by author stats

- **`git line-summary`**  
  - Show per‑author statistics based on lines of code instead of commits.  
  - Reports:
    - Project name
    - Total lines
    - Authors with line counts and percentages
  - Example output:
    - `project  : gulp`
    - `lines    : 3900`
    - Author line counts and percentages

- **`git effort`**  
  - Display effort metrics per file:
    - Number of commits touching each file
    - Number of active days for each file
  - Example output columns:
    - `file`
    - `commits`
    - `active days`

### Other Tools Listed (by category names)
*(Details for these are not in the provided snippet but are part of the directory’s table of contents.)*

- Workflow and branching helpers: Git Flow, Git Town, Legit, git-branchcut, git-project
- Collaboration and GitHub integration: Hub, Git My, Git Url
- Deployment and automation: Git Deploy
- Time and activity tracking: Git Cal, git-standup, git-spend
- Hooks and automation: Git Hooks
- Merge and history tools: Git Imerge, git-interactive-rebase-tool, git revise, filter-repo, git-jump
- Issue and task helpers: Git Issue, git-hound, git-recall
- Large files and storage: Git Large File Storage (Git LFS)
- Commit, diff, and blame enhancements: Git When Merged, Git Playback, Git Branch Status, Git Open, Recursive Blame, Git Hyper Blame, Git Word Blame, Diff So Fancy, git-fixup, git-fiddle, git-recent
- Security and secrets: Git Secret, Git Secrets, git-exfiltrate
- Statistics and analytics: Git Stats, git-spend
- Identity, profiles, and signatures: Git Signatures, Git Profile, git-user
- Misc and utilities: Git Up, Git Now, Git Plus, Git Test, Git Ink, Git Fire, Git Town, git-fs, Git Hound, git-fresh, Git Url, Commitizen, git-some, git-branchcut, git-spend

*(For full descriptions of each tool, refer directly to the GitHub directory page.)*

---

## Pricing

- This is an open-source curated list; access to the directory itself is free.  
- Individual tools listed may have their own licenses or pricing models, which must be checked per tool.
