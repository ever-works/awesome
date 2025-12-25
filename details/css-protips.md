---
title: CSS Protips
slug: css-protips
category: Themed Directories
tags:
  - css
  - web-development
  - frontend
source_url: https://github.com/AllThingsSmitty/css-protips#readme
featured: false

---

## Overview

CSS Protips is a curated collection of practical tips and patterns to help developers write clearer, more efficient, and more maintainable CSS. The repository focuses on cross‑browser consistency, modern layout techniques, accessibility, and leveraging newer CSS features.

## Features

### Collection Structure
- Organized list of individual “protips,” each with a short explanation and code example.
- Table of contents linking to each tip for quick navigation.
- External demos (e.g., CodePen) for some tips.
- Contribution guidelines for community additions and improvements.
- Translation section to access localized versions.

### Protips Covered

1. **Use a CSS Reset**  
   - Provides a clean slate across browsers by normalizing default styles.  
   - Example reset that removes default margins/padding and defines a box model:
     - `*`, `*::before`, `*::after { box-sizing: border-box; margin: 0; padding: 0; }`

2. **Inherit `box-sizing`**  
   - Set `box-sizing: border-box` on `html` and inherit it on all elements (`*`, `*::before`, `*::after`) for predictable sizing.

3. **Use `unset` Instead of Resetting All Properties**  
   - Use `all: unset` (or specific `unset` values) to revert styles to their inherited or initial value instead of manually resetting each property.

4. **Use `:not()` to Apply/Unapply Borders on Navigation**  
   - Apply borders to navigation items while excluding the last item using the `:not(:last-child)` selector.

5. **Check if Font Is Installed Locally**  
   - Use `local()` in `@font-face` to prefer a system-installed font before downloading a web font.

6. **Add `line-height` to `body`**  
   - Define a global `line-height` on `body` for consistent vertical rhythm and more readable text.

7. **Set `:focus` for Form Elements**  
   - Style `:focus` states on inputs, buttons, and other controls to improve keyboard accessibility and usability.

8. **Vertically-Center Anything**  
   - Use modern layout techniques (e.g., flexbox or grid) to vertically center content without hacks.

9. **Use `aspect-ratio` Instead of Height/Width**  
   - Maintain proportional boxes (e.g., videos, images, cards) using the `aspect-ratio` property instead of manually syncing height and width.

10. **Comma-Separated Lists**  
    - Use CSS pseudo-elements to automatically add commas between list items (excluding the last) in inline lists.

11. **Select Items Using Negative `nth-child`**  
    - Target the first N elements in a list using selectors like `:nth-child(-n + 3)`.

12. **Use SVG for Icons**  
    - Prefer SVG icons over raster images for scalability, crisp rendering, and easier styling.

13. **Use the "Lobotomized Owl" Selector**  
    - Use a global sibling selector (e.g., `* + *`) to apply consistent spacing between elements without individual margins.

14. **Use `max-height` for Pure CSS Sliders**  
    - Create basic show/hide or slider effects using `max-height` transitions instead of JavaScript.

15. **Equal-Width Table Cells**  
    - Use table layout properties (e.g., `table-layout: fixed`) for equal-width columns.

16. **Get Rid of Margin Hacks With Flexbox**  
    - Replace complex margin-based layouts with flexbox alignment and spacing utilities.

17. **Use Attribute Selectors with Empty Links**  
    - Detect and style anchors with empty `href` or missing text using attribute selectors (e.g., `a[href=""]`).

18. **Control Specificity Better With `:is()`**  
    - Use `:is()` to group selectors and manage specificity when targeting multiple patterns.

19. **Style "Default" Links**  
    - Provide base styling for unclassed links to ensure consistent appearance site-wide.

20. **Intrinsic Ratio Boxes**  
    - Create responsive, ratio-based boxes (e.g., 16:9) using padding or `aspect-ratio` for media containers.

21. **Style Broken Images**  
    - Apply fallback styles to images that fail to load (e.g., using `img::before`/`::after` or `object-fit`).

22. **Use `rem` for Global Sizing; Use `em` for Local Sizing**  
    - Define global scales (font sizes, spacing) with `rem` and component-relative scaling with `em` for flexible design.

23. **Hide Autoplay Videos That Aren't Muted**  
    - Target and hide or adjust autoplaying videos that lack `muted` to improve user experience.

24. **Use `:root` for Flexible Type**  
    - Set typographic scales and CSS variables on `:root` (e.g., fluid type, theme tokens) for centralized control.

25. **Set `font-size` on Form Elements for a Better Mobile Experience**  
    - Adjust form control font sizes to prevent zoom quirks and improve readability on mobile devices.

26. **Use Pointer Events to Control Mouse Events**  
    - Use `pointer-events` to allow clicks to pass through overlays or disable mouse interactions in specific contexts.

27. **Set `display: none` on Line Breaks Used as Spacing**  
    - Remove presentational `<br>` spacing by setting `br { display: none; }` in responsive contexts where layout changes.

28. **Use `:empty` to Hide Empty HTML Elements**  
    - Automatically hide elements without content using the `:empty` selector.

29. **Use `margin-inline` instead of `margin`**  
    - Use logical properties like `margin-inline` for direction-agnostic horizontal spacing, improving internationalization and RTL support.

## Translations

- Includes a dedicated Translations section pointing to community-maintained versions in other languages (linked from the repository).

## Contribution

- Public contribution guidelines available via `CONTRIBUTING.md` for proposing new tips, edits, and translations.

## Pricing

- Not a commercial product; the resource is free to access and use. No pricing plans.
