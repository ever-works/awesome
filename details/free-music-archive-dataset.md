# Free Music Archive Dataset

**Category:** Themed Directories  
**Tags:** datasets, audio, machine-learning  
**Website:** https://github.com/mdeff/fma  
**License:** MIT

## Description
The Free Music Archive (FMA) Dataset is an open collection of music audio files and rich metadata derived from the Free Music Archive. It is designed for music information retrieval (MIR) and machine learning research, and is commonly referenced in lists of machine learning benchmark datasets.

## Features
- **Open audio dataset** built from the Free Music Archive catalog.
- **Extensive metadata** for tracks, albums, artists, and genres (e.g., IDs, tags, hierarchy information).
- **Multiple dataset scales** (e.g., small / medium / large subsets) suitable for experiments of different sizes (implied by repo structure and typical FMA usage).
- **Research-focused design**, suitable for tasks such as:
  - Genre classification
  - Music recommendation
  - Audio feature learning / representation learning
  - General music information retrieval tasks
- **Audio feature extraction tools** via `features.py` and related scripts/notebooks.
- **Reproducible experiments** supported by Jupyter notebooks:
  - `analysis.ipynb` for dataset analysis and exploration
  - `baselines.ipynb` for baseline models and experiments
  - `creation.ipynb` for dataset creation workflow
  - `usage.ipynb` for example usage
- **Python package / tooling** with `setup.py`, `requirements.txt`, and helper scripts for working with the dataset.
- **Makefile-based automation** for common dataset processing and experiment tasks.
- **Utilities module** (`utils.py`) for common dataset operations and experiment helpers.
- **Figures and documentation assets** illustrating dataset structure and statistics (`figures/`, overview image).
- **Binder configuration** (`.binder/`) for running notebooks in an online environment (reproducible, no local setup).

## Technical Details
- Hosted as a public GitHub repository: `mdeff/fma`.
- MIT-licensed, allowing reuse in research and applications with attribution.
- Associated research paper: “FMA: A Dataset For Music Analysis” (arXiv:1612.01840).

## Pricing
- **Free**: The dataset and accompanying code are available at no cost under the MIT license.