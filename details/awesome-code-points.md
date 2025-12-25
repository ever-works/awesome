# Awesome Code Points

**Website:** https://github.com/Codepoints/awesome-codepoints#readme  
**Category:** Themed Directories  
**Tags:** awesome-lists, unicode, developer-tools

## Description
Awesome Code Points is a curated “awesome list” focusing on interesting or unusual Unicode code points, their behaviors, and related resources. It is aimed at developers, typographers, and anyone working with or exploring Unicode.

## Features

### Scope & Structure
- Curated list of notable Unicode characters and ranges.
- Organized sections, including:
  - Standalone code points
  - Code points that affect others
    - Breaking and gluing other characters
  - Record holders and extremes
  - For fun / novelty usage (e.g., games)
  - Other lists of code points
  - Contributing guidelines
  - License information

### Standalone Code Points
- **Box Drawing block (U+2500–U+257F)**
  - Provides line and box drawing characters for monospace command-line and TUI visualizations.
  - Example usage for simple frames and diagrams.
- **Block Elements block (U+2580–U+259F)**
  - Solid and partial block characters useful for text-mode graphics and progress bars.
- **U+2E2E REVERSED QUESTION MARK**
  - Often used as an “irony mark” for sarcasm or irony.
- **U+D800–U+DFFF Surrogate range**
  - Reserved exclusively for UTF-16 surrogate code points.
  - Not used as standalone characters; used internally for encoding non-BMP characters.
- **U+FEFF ZERO WIDTH NO-BREAK SPACE**
  - Semantically similar to U+2060 WORD JOINER.
  - Historically used as a Byte Order Mark (BOM) at the start of some UTF encodings.
  - Many tools strip it as metadata when found at the beginning of a file.
  - In software that does not treat it specially, it can cause unexpected behavior.
- **U+FFFD REPLACEMENT CHARACTER**
  - Displayed when a character cannot be decoded or rendered correctly.
  - Commonly appears when invalid UTF-8 sequences are encountered.
- **U+1D455 (missing code point)**
  - Slot that would correspond to a mathematical italic small “h”.
  - Intentionally not encoded because it would be identical in form to ℎ (U+210E, the Planck constant).
- **U+FF03 FULLWIDTH NUMBER SIGN**
  - The “fullwidth” (East Asian) form of the number sign `#`.
  - Often treated equivalently to the ASCII `#` (U+0023) by platforms such as Twitter, effectively acting as a “Japanese hashtag” character.

### Code Points That Affect Others
- **U+202D & U+202E (Directional Formatting)**
  - Change the text direction (e.g., left-to-right vs. right-to-left overrides).
  - Can affect how surrounding text is displayed, especially in bidirectional contexts.
  - Known for potential misuse/abuse in code or text obfuscation (illustrated in linked XKCD comic).
- **U+FE0E VARIATION SELECTOR-15**
  - A variation selector that forces a text-style (black-and-white / non-emoji) rendering of certain characters that have both emoji and text presentations.

### Additional Sections (as referenced in the table of contents)
- **Breaking and Gluing Characters**
  - Subsection under “Code points that affect others” focused on characters that influence line breaks or join/split other characters (details in full list on the repo).
- **Record Holders and Extremes**
  - Code points noted for extreme values or unusual status (e.g., highest code points, oddities, rare categories).
- **For Funsies / Games**
  - Examples of playful or game-related uses of Unicode characters.
- **Other Lists of Code Points**
  - Links to additional collections or references of interesting Unicode characters.
- **Contributing**
  - Guidelines for submitting new interesting code points or improvements to the list.
- **License**
  - The list is published with an open license (details in the repository).

## Pricing
Not applicable. Awesome Code Points is an open, GitHub-hosted curated list and is free to use.