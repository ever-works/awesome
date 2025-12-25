# jQuery Tips Everyone Should Know

A curated collection of concise, practical jQuery tips and patterns to improve day‑to‑day jQuery development.

## Overview

- **Type:** Open-source tip collection / code snippets
- **Category:** Themed directories
- **Topics:** JavaScript, jQuery, front-end development
- **Source:** <https://github.com/AllThingsSmitty/jquery-tips-everyone-should-know#readme>

## Features

### Scope of Content

A growing list of simple, focused tips covering common jQuery usage patterns and edge cases, including:

1. **Use `noConflict()`**
   - Avoid conflicts when multiple libraries use the `$` alias.
   - Demonstrates using `jQuery` instead of `$`.
   - Shows how to create a custom alias when multiple jQuery versions are present.

2. **Checking if jQuery Loaded**
   - Pattern for safely detecting whether jQuery is available (`typeof jQuery === "undefined"`).
   - Encourages defensive checks before using jQuery APIs.

3. **Check Whether an Element Exists**
   - Idiomatic use of `.length` on a jQuery selection to verify a DOM element is present before operating on it.

4. **Use `.on()` Binding Instead of `.click()`**
   - Promotes `.on()` as the preferred event binding method.
   - Shows combining multiple events in one binding (e.g., `click`, `tap`, `hover`).
   - Explains event delegation so dynamically created elements are automatically handled.
   - Demonstrates event namespaces (e.g., `.on('click.menuOpening')`) to enable precise unbinding with `.off()`.

5. **Back to Top Button**
   - Pattern (referenced in the list) for implementing a scroll-to-top button with jQuery.

6. **Preload Images**
   - Technique (referenced) for loading images ahead of time to reduce perceived load times.

7. **Checking If Images Are Loaded**
   - Tips for detecting when images are fully loaded before performing layout or effects.

8. **Fix Broken Images Automatically**
   - Pattern for detecting failed image loads and replacing them with fallback sources.

9. **Post a Form with AJAX**
   - Shows how to submit forms asynchronously using jQuery’s AJAX capabilities.

10. **Toggle Classes on Hover**
    - Simple pattern for using hover events to add/remove/toggle CSS classes.

11. **Disabling Input Fields**
    - Uses jQuery to enable/disable input elements dynamically.

12. **Stop the Loading of Links**
    - Demonstrates how to prevent default link navigation (e.g., `event.preventDefault()`).

13. **Cache jQuery Selectors**
    - Encourages storing frequently used jQuery selections in variables to avoid repeated DOM queries and improve performance.

14. **Toggle Fade/Slide**
    - Shows simple patterns for toggling visibility with jQuery animation helpers (`fade*`, `slide*`).

15. **Simple Accordion**
    - Demonstrates a minimal accordion implementation using jQuery for show/hide sections.

16. **Make Two Divs the Same Height**
    - Pattern for matching heights of two DOM elements via jQuery.

17. **Open External Links in New Tab/Window**
    - Example of detecting external links and adding `target="_blank"` behavior.

18. **Find Element By Text**
    - Pattern for selecting elements whose text matches a string.

19. **Trigger on Visibility Change**
    - Shows how to trigger behavior when a page or element visibility changes.

20. **AJAX Call Error Handling**
    - Illustrates proper error handling with jQuery’s AJAX methods.

21. **Chain Plugin Calls**
    - Demonstrates chaining patterns with jQuery plugins for cleaner, more fluent code.

22. **Sort List Items Alphabetically**
    - Example of reordering list items using jQuery.

23. **Disable Right-Click**
    - Pattern for intercepting and blocking the context menu event.

### Additional Repository Sections

- **Translations**
  - The project provides or links to translations of the tips in multiple languages (where available).

- **Contribution Guidelines**
  - A `CONTRIBUTING.md` file outlines how to propose new tips or improvements (coding style, pull request process, etc.).

## Pricing

- **Cost:** Free (open-source GitHub repository; no pricing plans mentioned).