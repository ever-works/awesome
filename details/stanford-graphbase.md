# Stanford GraphBase

**Category:** Themed Directories  
**Tags:** datasets, graph, algorithms  
**Source:** <https://cs.stanford.edu/~knuth/sgb.html>

Stanford GraphBase is Donald Knuth’s public-domain collection of graph-related programs and combinatorial datasets, designed as a workbench for experimenting with graph algorithms and data structures. It accompanies the book *The Stanford GraphBase: A Platform for Combinatorial Computing* and is widely used as a standard source of benchmark graph instances.

---

## Features

### Core Concept
- Platform for combinatorial computing centered on graphs and related structures.
- Designed to support experimentation and benchmarking of graph algorithms and data structures.
- Closely integrated with the literate programming style demonstrated in Knuth’s book.

### Programs and Codebase
- Contains more than 30 literate programming examples; each is a “programmatic essay” combining human-readable exposition with machine-executable code.
- Programs illustrate state-of-the-art explanations (at the time of writing) of key algorithms and data structures.
- Highly portable C code, historically compiled on a wide variety of systems.
- Public-domain source for all programs and data.
- Original C code uses pre-prototype style; compilation on modern compilers typically requires flags like `-ansi` or `-std=c90`.
- A modernized, actively maintained version is available on GitHub by Andreas Scherer: <https://github.com/ascherer/sgb>.

### Data Sets and Graph Instances
- Standardized datasets for:
  - Benchmarking and comparing competing graph algorithms.
  - Demonstration programs.
  - Games and experimental studies.
- Example downloadable data files include:
  - `sgb-words.txt`: list of 5,757 five-letter English words.
  - `contiguous-usa.dat`: adjacency data for the contiguous United States and DC.
- Sample graph files from TAOCP and related work (in `.gb` format), such as:
  - `knight3.gb`: instance related to “long and skinny knight’s tours”, with a verbose text printout `knight3.txt`.
  - `somap3.gb`: the Somap of Berlekamp, Conway, and Guy, with all possible dotted edges; verbose printout and explanation in `somap-list.txt`.
  - `somap2.gb`: Somap with only solid edges.

### Integration with The Art of Computer Programming (TAOCP)
- Stanford GraphBase is used extensively in Volume 4 of *The Art of Computer Programming*.
- Hundreds of example programs using GraphBase are planned as electronic supplements to TAOCP Volume 4.

### Distribution and Access
- Master public-domain sources (programs and data) available via:
  - FTP archive: `ftp.cs.stanford.edu` in directory `~ftp/pub/sgb` (e.g., `sgb.tar.gz`).
  - GitHub mirror/update: <https://github.com/ascherer/sgb>.
- Referenced and described in external resources such as the Stony Brook Algorithm Repository.

### Challenge Problems
- The book includes open challenge problems, encouraging further research.
- Notable example: graph-based analysis of the 1990 U.S. college football season to find maximal score differences (e.g., Stanford vs. Harvard) via chains of game results.
- Documented improvements over time on this challenge, demonstrating practical use of GraphBase data and algorithms.

### Recognition
- The book *The Stanford GraphBase: A Platform for Combinatorial Computing* was cited by the Association of American Publishers as the best new book in Computer Science in 1994.

---

## Access & Implementation Notes
- **Source download (classic master):** <https://cs.stanford.edu/pub/sgb/sgb.tar.gz>
- **Modernized version:** <https://github.com/ascherer/sgb>
- **Compilation tip for original sources:** add `-ansi` or `-std=c90` when compiling C programs with modern compilers (e.g., `gcc`).

---

## Pricing
- Sources and data are in the public domain and freely available to download and use.
- The accompanying book is sold via publishers (e.g., ACM Press, Addison-Wesley); pricing depends on the retailer and is not specified on the source page.