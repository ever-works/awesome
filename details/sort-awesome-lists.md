## Overview

sort-awesome-lists is a Go-based CLI application with zero external dependencies that sorts awesome lists (e.g., awesome-go, awesome-rust) by the number of stars for GitHub repositories in each section.

## Features

- Parses markdown README.md files and identifies GitHub repositories from bullet points via direct links (github.com/username/repo or username.github.io/repo).
- For project websites without direct GitHub links, downloads and parses HTML to find GitHub repository links.
- Fetches star counts using GitHub API (requires personal access token for rate limits).
- Sorts sections independently in descending order by stars.
- Configurable concurrent API requests per block (-bs flag, default 5).
- Outputs to file (-o flag) or stdout.
- Verbose debug mode (-v flag).

## Building

go build -o sort-awesome-lists main.go

## Usage

./sort-awesome-lists -t="$GITHUB_TOKEN" -o="output.md" "https://raw.githubusercontent.com/avelino/awesome-go/master/README.md"

## Known Issues

- Cannot detect GitHub links on JavaScript-heavy sites requiring client-side rendering.

## Pricing

Free and open-source.