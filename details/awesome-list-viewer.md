## Overview

Awesome List Viewer is a backend utility for discovering and managing GitHub "awesome lists". It downloads metadata about curated awesome lists from GitHub, stores the data as JSON, and makes it available for querying through a dedicated frontend application.

## Features

- Automated Extraction: Parses a configurable list of GitHub awesome lists, and extracts metadata (description, topics, stars, language, etc.) from each repository found.
- Efficient Storage: Saves awesome list and repository metadata in structured JSON files, optimized for fast querying.
- Topic Categorization: Groups repositories by topics for easier discovery.
- Frontend Integration: Designed to power the frontend app for user-friendly browsing and search.
- Easy Updates: Can refresh all data with a single run, using your GitHub API token.

## How It Works

- Fetch Awesome Lists: The backend reads a list of awesome GitHub repositories from lists.txt.
- Download Metadata: For each awesome list, it fetches the README, extracts repositories, and downloads metadata (stars, topics, etc.) via the GitHub API.
- Store as JSON: Metadata is saved in the var/ directory (var/awesome/, var/repo/, var/topic/).
- Frontend Consumption: The generated JSON files are intended to be copied to the frontend repo (managing-awesome-lists-frontend) for browsing and querying.

## Usage

### Prerequisites

- Python 3.10+
- A GitHub API access token
- `pip install -r requirements.txt`
- Create `.env` with `CREDENTIALS=your_github_token_here`

### Running the Backend

`python app.py`

This parses lists in lists.txt, downloads metadata, generates JSON in var/, and copies to frontend as configured.

## Data Model

Each repository entry includes:

- full_name – owner/repo
- description
- topics – list of topics
- created_at, pushed_at
- stargazers_count
- language

Awesome lists and topics are grouped and serialized for efficient frontend querying.

## License

MIT License.